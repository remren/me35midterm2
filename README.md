# me35midterm2
Release Version for the Midterm2 Project in ME35: Robotics I

## Repository Overview
* extras: Contains the .svg file for the construction of the front and back plates.
* for_pc: All code that will run on the comptuer. Currently only saved code from the PyScript file.
* libraries: All files that should be downloaded to the Pico's internal storage. Will be called upon in its main.
	* You may need to change connect_pico_to_wifi.py to properly connect to your Wi-Fi network.
* main_pc_airtable_to_adafruit.py: This relays data from AirTable to AdafruitIO. It will run in a local Python 3 interpreter of your choosing. I used Thonny.
* main_pico_comms_and_display.py: Should be saved as main.py on the Pico's internal storage

## External Library Credits
Big shoutouts to these resources and repositories. They've greatly helped me in making this possible!
* Thermistor Calibration: https://halvorsen.blog/documents/technology/iot/pico/pico_thermisor.php
* Image Processing: https://stackoverflow.com/questions/44588279/find-and-draw-the-largest-contour-in-opencv-on-a-specific-color-python
* mqtt to AdafruitIO: https://github.com/adafruit/Adafruit_IO_Python/tree/master

## Additional Required Libraries
* Networking: urequests, requests, ubinascii, network, paho.mqtt.client, json
* Image Processing: OpenCV, numpy
* Pico: machine, time
