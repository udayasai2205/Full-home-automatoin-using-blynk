Components Required:

ESP8266 Module (NodeMCU or similar)
DHT11 Sensor
MQ2 Gas Sensor
PIR Motion Sensor
Ultrasonic Sensor (HC-SR04)
Buzzer
Relay Module (2-channel)
LCD Display (I2C)
Resistors (as needed)
Breadboard and Jumper Wires
Circuit Connections
ESP8266 Connections:

D0 (GPIO16): Connect to Buzzer (one terminal to D0 and the other to GND).
D3 (GPIO0): Connect to DHT11 Data Pin.
D4 (GPIO2): Connect to Trig of Ultrasonic Sensor.
D5 (GPIO14): Connect to Echo of Ultrasonic Sensor.
D6 (GPIO12): Connect to PIR Motion Sensor output.
D7 (GPIO13): Connect to Relay 1 control pin.
D8 (GPIO15): Connect to Relay 2 control pin.
A0 (ADC0): Connect to MQ2 Analog output.
DHT11 Sensor:

VCC: Connect to 5V
GND: Connect to GND
Data Pin: Connect to D3 (GPIO0)
MQ2 Gas Sensor:

VCC: Connect to 5V
GND: Connect to GND
Analog Output: Connect to A0 (ADC0)
PIR Motion Sensor:

VCC: Connect to 5V
GND: Connect to GND
Output: Connect to D6 (GPIO12)
Ultrasonic Sensor (HC-SR04):

VCC: Connect to 5V
GND: Connect to GND
Trig: Connect to D4 (GPIO2)
Echo: Connect to D5 (GPIO14)
Relay Module:

Relay 1 Control Pin: Connect to D7 (GPIO13)
Relay 2 Control Pin: Connect to D8 (GPIO15)
VCC: Connect to 5V
GND: Connect to GND
Connect normally open (NO) or normally closed (NC) contacts to the appliances.
LCD Display (I2C):

VCC: Connect to 5V
GND: Connect to GND
SDA: Connect to D1 (GPIO5)
SCL: Connect to D2 (GPIO4)