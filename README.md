# ESP01-WIFI-REPEATER
Make a cheap wifi repeater using Esp01(ESP8266-01) Arduino IDE
Connect your Wifi Module using a USB TTL converter ( In my case i used USB-TTL converter CH340 one)
Install the USB-TTL module drivers.
Simply Download the .ino file or copy paste the code in Arduino IDE
To install the ESP8266 board in your Arduino IDE, follow these next instructions: (If already installed then skip to next step)
1. In your Arduino IDE, go to File> Preferences
2. Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into the “Additional Boards Manager URLs” field as shown in the figure below. Then, click the “OK” button:
3. (Note: if you already have the ESP32 boards URL, you can separate the URLs with a comma as follows: https://dl.espressif.com/dl/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json
4. Open the Boards Manager. Go to Tools > Board > Boards Manager…
5. Search for ESP8266 and press install button for the “ESP8266 by ESP8266 Community“:
6. That’s it. It should be installed after a few seconds.
7. Plug your board to your computer. Make sure you have the right board selected
8. You also need to select the Port:
9. Then, copy the code provided in above sketch.
10. Click the “Upload” button in the Arduino IDE and wait a few seconds until you see the message “Done uploading.” in the bottom left corner.
11. After uploading sketch, Unplug or restart the module.
12. Connect it to a power source (3.3V) or if you are using USB-TTL Module then use any power bank or smartphone charger to power it.
13. Thats it !!! Enjoy with extended wifi signal.
