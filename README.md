# WICS-Install
Installation of nowRail and WICS add-on software to the ESP32 Microcontroller
---
- Installation of nowRail and WICS software delete existing content on the Microcontroller.
- If upgrading the software? Please copy existing configuration files first from littleFS.
- Only Install the software if you have the associated WICS Board (MCU & PIN dependent).
- For the Espressif ESP32-S3 connect the USB cable to the left Micro-USB (UART).
- For other ESP32 Microcontroller use the USB-C connector marked USB. 
- If you get problem with "hanging or installation not starting" please set 
  the Microcontroller into "Flash Mode" by holding down the right Boot button 
  on the ESP32-C6/S3 (Gateway) and the left button on the ESP32-S3 (PCA9685) 
  while you powering up (connecting the USB cable) the Microcontroller.
  
  Installation:
  - 1. Connect the Microcontroller with a "real" USB-cable (not a charging cable). 
  - 2. Select the WICS Board from the menu/submwenu and click the "Connect" button.
  - 3. Follow the instructions on the screen.
  - 4. When done, Reboot the Microcontroller.
  - 5. Upload your configuration file (using ESP-Connect).
