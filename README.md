# IOT-based-food-spoilage-detection.
The food spoilage detection system developed in this mini-project is based
on an Arduino board, which is connected to gas sensor. The MQ4 sensor is
used to detect the emission of methane gases. The ESP8266 Wi-Fi Module
is used to connect the Arduino board to the internet and send the data to a
blynk server for real-time monitoring. The sensors are calibrated to detect
visible signs of spoilage and low amounts of gas emission, which are
indicators of food spoilage.

How to connect Buzzer, LEDs, MQ4 Sensor and NodeMCU to Arduino
UNO R3:

1)Connect Buzzer to Arduino UNO:
i)Positive terminal(long end) should be connected to any digital pin say digital pin D10
on Arduino
ii)Negative terminal(short end) should connected to common ground on breadboard.
2) Connect LEDs to Arduino UNO:
i)Positive terminal to digital pin D13 or any other digital pin on Arduino
ii)Negative terminal to common ground on bread board.
3) Connect NodeMCU to Arduino UNO:
i)Here we are using NodeMCU with ESP8266 12E WiFi Module. Serial communication
is required to transfer data between arduino and nodemcu.
ii)Rx of NodeMCU to any digital pin say D9
iii)Tx of NodeMCU to any digital pin say D8
iv)GND to GND of arduino(or common GND)
v)Vin pin of NodeMCU to 3.3v supply of Arduino.
4) How to connect MQ4 Sensor to Arduino UNO R3:
i)Analaog pin of sensor i.e AD to A5 or any analog pin of Arduino
ii)DO digital pin is kept as it is
iii)GND pin of sensor is connected to GND pin of arduino (or common GND)
iv)Vcc pin of sensor 5v power supply pin of Arduino.

![image](https://github.com/user-attachments/assets/71945dc5-ff5c-4d3d-af49-58ae37a085b1)
