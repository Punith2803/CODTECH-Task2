Name : PUNITH N 
Company :CODTECH IT SOLUTIONS
ID:CT08DS1365 Domain :IOT 
Duration :1st JUNE 2024 to 30Th JUNE 2024
Mentor :SRAVANI GOUNI# CODTECH-Task2


ESP 32 Bluetooth Enabled controller 
Components Used
ESP32 development board
DHT11 temperature and humidity sensor
Libraries Used
BluetoothSerial
DHT sensor library
Setup
Hardware Connections:

Connect the DHT11 sensor to the ESP32 board. Typically, connect the sensor's data pin to GPIO 2 (defined as dhtPin in the code).
Software Setup:

Install the ESP32 board support in the Arduino IDE if not already installed.
Include the required libraries:
BluetoothSerial library for ESP32.
DHT sensor library.
Upload the Code:

Upload the provided Arduino sketch (ESP32_BT_Server.ino) to your ESP32 board using the Arduino IDE.
Usage
Monitor Serial Output:

Open the Arduino IDE Serial Monitor to view temperature and humidity data being read from the DHT11 sensor.
Connect via Bluetooth:

Pair your ESP32 device with a Bluetooth terminal app on your smartphone or computer.
Search for Bluetooth devices and connect to "ESP32_BT_Server".
Once connected, you should see temperature and humidity readings displayed in the terminal app.
Notes
Ensure the DHT11 sensor is properly connected to the ESP32 board.
Make sure your ESP32 board has Bluetooth capabilities (most do).
Adjust the dhtPin and DHTTYPE definitions in the code if using a different GPIO pin or DHT sensor type.
