# IoT Smart Greenhouse Project

This project is a **smart greenhouse system** designed to optimize plant growth using **IoT technology**. It automates the control of key environmental factors such as **soil moisture**, **temperature**, and **light intensity**. The system collects data from various sensors, processes it, and adjusts the conditions using actuators to ensure optimal plant growth with minimal human intervention.

## Features

- **Automated Control** of environmental factors such as soil moisture, temperature, and light.
- **Efficient Irrigation** that conserves water by only providing the required amount based on soil moisture levels.
- **Customizable Light Exposure** to match the specific needs of different plant species.

## Sensors Used

- **Temperature Sensor (LM335)**: Measures the greenhouse's air temperature to maintain optimal conditions.
- **Soil Moisture Sensor**: Monitors the moisture content in the soil to trigger the irrigation system when necessary.
- **Humidity Sensor (DHT11/DHT22)**: Measures the relative humidity in the air to manage ventilation and other factors.
- **Light Sensor (LDR)**: Monitors light intensity and adjusts artificial lighting to ensure plants receive the appropriate amount of light.

## Actuators Used

- **Solenoid Valve**: Controls water flow for the irrigation system, activated when the soil moisture falls below a certain threshold.
- **Servo Motor**: Adjusts blinds or shading mechanisms to regulate the amount of natural light entering the greenhouse.

## System Architecture

- **Sensors** gather data on environmental conditions such as temperature, humidity, soil moisture, and light intensity.
- **Microcontroller** processes the data and sends commands to the actuators to adjust water supply and light exposure as needed.
