Name:KADI YASWANTH 
COMPANY:CODTECH IT SOLUTIONS 
ID:CT12DS2711
DOMAIN: EMBEDDED SYSTEMS
DURATION: 8 WEEKS
MENTOR:NEELA SANTHOSH KUMAR

OVERVIEW OF THE PROJECT

PROJECT: TEMPERATURE AND HUMIDITY MONITORING WITH DHT SENSOR

Objective

To use an Arduino board to read environmental data such as temperature and humidity.
To display the collected data on an output interface like a serial monitor or an LCD screen.
Key Components
Arduino Board (e.g., Arduino Uno):

The main controller that reads sensor data and processes it.
DHT11 or DHT22 Sensor:

A sensor used to measure both temperature and humidity. The DHT11 is more basic, whereas the DHT22 offers higher accuracy and wider ranges for both temperature and humidity.
Jumper Wires:

Used to connect the sensor to the Arduino.
Breadboard (optional):

Used for organizing and holding components together for easy connections.
Resistor (typically 10kΩ):

A pull-up resistor that may be needed for proper data transmission between the sensor and Arduino.
LCD or LED Display (optional):

An output device to display the temperature and humidity data in real-time.
Power Supply:

Typically provided via a USB cable or a battery to power the Arduino.
Working Principle
The DHT sensor works by:

Measuring temperature: It has a built-in thermistor that detects changes in temperature.
Measuring humidity: It also has a capacitive humidity sensor that detects the moisture level in the air.
The sensor then sends digital data to the Arduino microcontroller, which processes the information and outputs it to a display or serial monitor.

How the System Works
Sensor Data Collection:

The sensor measures the temperature and humidity of the surrounding environment.
The sensor transmits this data in digital format to the Arduino through a single data wire.
Data Processing by Arduino:

The Arduino board reads the data sent from the sensor.
It then processes this data and converts it into human-readable values, typically in Celsius for temperature and percentage for humidity.
Displaying the Data:

The data is displayed on the serial monitor of the Arduino IDE, or it can be shown on a Liquid Crystal Display (LCD), if used.
Optional Features:

Data logging: The data could be stored on an SD card for future analysis.
Wireless transmission: The data could be sent to a remote server or a web application using Wi-Fi or Bluetooth.
Control systems: Use the data to trigger actions (e.g., turn on a fan if the temperature exceeds a certain limit).
Connections
VCC Pin: Connects to the 5V pin of the Arduino to power the sensor.
GND Pin: Connects to the ground (GND) pin on the Arduino.
Data Pin: The digital signal pin (data pin) connects to a chosen digital input pin on the Arduino (e.g., Pin 7).
Optionally, a 10kΩ pull-up resistor may be placed between the VCC and Data pins for more reliable communication.
Applications
Weather Stations: To monitor environmental conditions like temperature and humidity.
Greenhouses: To ensure the optimal environment for plants.
Home Automation: To integrate with other systems like HVAC for automatic climate control.
Data Logging Systems: For scientific experiments or analysis of environmental data over time.
Potential Enhancements
Wireless Monitoring: You can add a Wi-Fi module (e.g., ESP8266) to send the data to the cloud or a mobile app.
Alerts: Set temperature or humidity thresholds, and use the system to send alerts or notifications if those thresholds are exceeded (e.g., for controlling heating, cooling, or ventilation).
Multiple Sensors: Add more sensors to monitor temperature and humidity in different parts of a room or building.
Data Visualization: Use software to visualize the data in charts or graphs for better analysis.
This project is an excellent hands-on way to learn about sensors, environmental monitoring, and how to interface them with microcontrollers like Arduino. It can be adapted for various applications and is a good foundation for more advanced IoT and automation projects.






