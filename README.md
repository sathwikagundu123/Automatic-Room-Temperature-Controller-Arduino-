# Automatic-Room-Temperature-Controller-Arduino-

# Automatic Room Temperature Controller

## Overview
This project is an **Automatic Room Temperature Controller** designed to maintain a comfortable environment by regulating temperature based on user-defined settings. The system continuously monitors room temperature using sensors and controls heating or cooling devices accordingly.

## Features
- **Real-Time Temperature Monitoring**: Uses a temperature sensor (e.g., DHT11, DHT22) to continuously monitor the room temperature.
- **Automatic Control**: Activates or deactivates heating/cooling devices based on the desired temperature range.
- **User-Defined Settings**: Allows users to set the desired temperature threshold.
- **LCD Display**: Displays the current temperature, set temperature, and system status.
- **Energy Efficient**: Optimizes energy usage by operating only when necessary.

## Components Required
- **Microcontroller** (e.g., Arduino, Raspberry Pi)
- **Temperature Sensor** (e.g., DHT11, DHT22)
- **Relay Module**
- **LCD Display**
- **Heating/Cooling Devices** (e.g., fan, heater)
- **Miscellaneous** (wires, power supply, etc.)

## Circuit Connection
1. Connect the **temperature sensor** (DHT11/DHT22) to the microcontroller.
2. Interface the **relay module** to control the heating/cooling devices.
3. Attach an **LCD display** to show temperature readings and system status.
4. Ensure the microcontroller is powered with an appropriate **power supply**.
5. **Placement Tip**: Position the temperature sensor at the end of the board for easy temperature adjustments.

## Code Deployment
1. Upload the Arduino code to the microcontroller.
2. Set a **cutoff temperature** as per the desired conditions.
3. The system will automatically regulate the temperature by turning devices **on/off** based on the set threshold.

## Safety Precautions
- Use a **regulated power supply** to prevent damage to the Arduino.
- Verify **circuit connections** before powering the system.
- Use **good quality components** for optimal performance and safety.

## How It Works
1. The **temperature sensor** continuously monitors the room temperature.
2. The **microcontroller** processes the data and compares it with the **user-defined temperature range**.
3. If the temperature exceeds the set limit, the **cooling device (fan/AC)** turns **on**.
4. If the temperature drops below the set limit, the **heating device (heater)** turns **on**.
5. The **LCD display** provides real-time temperature updates and system status.

## Applications
- Home automation
- Smart offices
- Industrial temperature regulation
- Server room cooling management

## Conclusion
The **Automatic Room Temperature Controller** is an energy-efficient system that ensures a comfortable environment by automatically managing heating and cooling devices. With real-time monitoring and user-defined settings, it provides a smart and practical solution for temperature control.




