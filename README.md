# About

This repo holds the code for Suprabit task related to job interview for Jurica Bilić.
Code was developed and tested on following boards:
* ESP32 DevkitC V4
* ESPDuino-32

## Wiring

Wiring is fairly simple and involves a DHT22 sensor and 10k resistor. Flashing of code to ESP will not be explained.
Image below shows how to do it:
![This is an image](https://i2.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/03/ESP32-DHT-wiring_bb.png?resize=768%2C851&quality=100&strip=all&ssl=1)
_Image taken from randomnerdtutorials.com_

## How to use

After uploading the code, either leave it connected and powered by USB on PC. To be on the safe side, restart ESP (button EN) after uploading.
Second option is to connect ESP to a dedicated power source (wall adapter for example), with a 5V/1A output.

It takes around 5-10 seconds for a WiFi AP to show up. AP is calles __"Suprabit ESP task"__ and password is __12345678jure__ .

Connect to AP. AP is not connected to Internet.
Open browser and input __192.168.4.2/sensor__
DHCP is used to create IP address and instances for viewing sensor data.

Website will open showing graph with temperature and humidity data read from DHT sensor.




DATE: December 11th 2021.