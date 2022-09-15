
# Farm Irrigation System

In this irrigation system we want to build contains temperature and humidity sensors that control the
water supply in the farm. Using sensor data, We want to build a machine learning model that
predicts how much water (in percentage) should be supplied to the farm.


## Hardware Requirements

1. Raspberry pi
2. DHT11 Sensor
3. LCD
4. Jumper wires
5. Breadboard


## Software Requirements

Dependencies Installation

 
We need to install python, pip and mqtt by running following commands in command prompt.

--> "sudo apt update"

--> "sudo apt install python3"

--> "sudo apt install python3-pip"

--> "pip3 install paho-mqtt"

--> "sudo apt-get install rpi.gpio"

To install the Adafruit DHT11 library:

1. Enter this at the command prompt to download the library:

git clone https://github.com/adafruit/Adafruit_Python_DHT.git

2. Change directories with:

cd Adafruit_Python_DHT

3. Now enter this:

--> sudo apt-get install build-essential python-dev

4. Then install the library with:

--> sudo python setup.py install


## Hardware setup

To connect DHT11 sensor and LCD with Raspberry pi, Refer the connection diagram mentioned in our report.

## Contact

Link: [https://github.com/anshIITK/IOT-assgn]


