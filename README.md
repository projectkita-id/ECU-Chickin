# ECU

This project is an **Electrical Control Unit (ECU)** designed to monitor and control various electrical and temperature parameters within a system. It utilizes multiple sensors and modules to collect data and control hardware devices such as relays and servos.  
  
## Features  
  
- **Temperature Monitoring**: Uses the MAX6675 sensor to read temperature from two thermocouples.  
- **Current and Voltage Measurement**: Utilizes the INA219 to measure current and voltage.  
- **Fuel Level Sensor**: Measures the fuel level in the tank using an analog sensor.  
- **RPM Calculation**: Calculates revolutions per minute (RPM) using an infrared sensor.  
- **Relay Control**: Controls multiple relays to turn devices on or off.  
- **Servo Control**: Adjusts the position of a servo based on received data.  
- **RS-485 Communication**: Uses the Modbus protocol for communication with other devices.  
- **LCD Interface**: Displays important information such as voltage, current, temperature, RPM, and fuel level.  
  
## Prerequisites  
  
Before you begin, ensure you have the following installed:  
  
- Arduino IDE  
- Required libraries:  
  - `Wire`  
  - `LiquidCrystal_I2C`  https://github.com/johnrickman/LiquidCrystal_I2C.git
  - `ModbusRTUSlave`  https://github.com/CMB27/ModbusRTUSlave.git
  - `Adafruit_INA219`  https://github.com/adafruit/Adafruit_INA219.git
  - `MAX6675_Thermocouple`  https://github.com/suoapvs/MAX6675_Thermocouple.git
  - `Servo`  
  - `EEPROM`  
  
## Installation  
  
Follow these steps to install and run this project on your local machine:  
  
1. Clone this repository:  
2. Open the project in the Arduino IDE.  
3. Ensure all required libraries are installed.  
4. Upload the code to your Arduino board.  
  
## Usage  
  
Once the code is uploaded, the project will start monitoring and controlling electrical and temperature parameters. Information will be displayed on the LCD, and data will be transmitted via RS-485 communication. You can control relays and servos based on the received data.  
