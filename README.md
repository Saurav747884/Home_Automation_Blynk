# IoT-Based Home Automation System 
Project Overview
This project focuses on leveraging IoT technology to create an intelligent and automated home system. With this system, users can control and monitor various home appliances using their smartphones or internet-enabled devices. The automation also includes the capability to perform predefined tasks, enhancing convenience and energy efficiency. For instance, tasks like automatically managing lighting, temperature, and water levels are made seamless with this system.

The project includes three key automation features:

1. Garden Light Automation
The system intelligently controls garden lights based on the intensity of ambient light detected by an LDR (Light Dependent Resistor). Lights remain OFF during daylight hours and automatically switch ON as it gets darker.

2. Room Temperature Monitoring
Using an LM35 temperature sensor, the system continuously monitors the room's temperature. If the temperature exceeds 35°C while the heater is ON, the system automatically turns OFF the heater to ensure safety and prevent overheating.

3. Water Level Management
The water tank's inlet and outlet valves are controlled via serial communication. When the water level reaches full capacity, the inlet valve is turned OFF. If the water level drops below 2000 liters, the inlet valve is automatically activated to refill the tank.

# Technologies and Tools Used

Arduino IDE: Used for writing and uploading the hardware code.
PicsimLab: Simulated the hardware components and their functionalities.
Virtual COM Port: Established a serial communication link between PicsimLab, the virtual Arduino, and the Arduino IDE.
Blynk IoT App: Enabled cloud-based features for data retrieval and storage, allowing real-time monitoring and control via a smartphone.
Components and Peripherals

LDR Sensor
Temperature System: Includes a heater, cooler, and an LM35 temperature sensor.
I2C-Based Character LCD (CLCD) for real-time data display.
LEDs for status indication.
Ethernet Shield for internet connectivity.
Serial Remote Tank for water level monitoring and valve control.
This project is fully simulated and demonstrates the potential of IoT in home automation by combining sensors, actuators, and cloud-based technologies.
