There are following feature in this project
1. Selection of following Fule name for Show on Single coulure P10 Display by Advance Page.
 a) Petrol b) Diesel c) Power d) Power95  e) Turbojet   f) CNG
2. Type the Fule Rate by Home page and submit.
3. Type Device ID for Display and submit.
4. Select brightness of display.
   a) Clock based    b) Live Based.
5. Go to OTA webpage with using User Id " admin" and Password "admin"
6. Select .bin program file and submit for update the firmware of ESP.
7. Process for firmware uploading on ESP32 by Arduino IDE method.
   a) Download Arduino IDE
   b) Paste this link on File>Preferences "https://dl.espressif.com/dl/package_esp32_index.json".
c) Select board name "ESP32" 1.0.5 version.
d) Attachment "DMD32-main" library in sketch <include Library<ZIP file.
   e) Download library "RTClib by Adafruit" in library manager.
8. Hardware Interface.
        Programmer             ESP32 Board
       1. Voltage 3.3 v  -     P2 connector in vcc
       2. RX                   TX
       3. TX                   RX
       4. GND                  GND
9. Process for firmware uploading on ESP32 by flash_download_tool method.
   a) download and Install flash_download_tool by google.
   b) Open This IDE and select chipType as "ESP32".
   C) select Workmode as "Develop". then submit by ok button.
   d) choose "ino.bin" file from buit folder and set the address "0x10000".
e) chosse ino.partions" file from built folder  and set address "0x8000".
   f) connect hadware as point number 8.
g) Set speed as 40MHz, SPI Mode as DIO and CHECK BOX ON DoNotChgBin.
h) select COM. and also select boad Rate as 921600.
i) Click on Start bottun.