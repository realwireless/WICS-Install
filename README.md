# WICS-Install
Installation of nowRail and WICS add-on software to the ESP32 Microcontroller
---
- Installation of nowRail and WICS software delete existing content on the Microcontroller.
- If upgrading the software? Please copy existing configuration files first from littleFS.
- Only Install the software if you have the associated WICS Board (MCU & PIN dependent).
- Espressif ESP32-S3 is using Micro-USB, the other ESP32 models is using USB-C. 
- If you get problem with "hanging or installation not starting" please set 
  the Microcontroller into "Flash Mode" by holding down the "Boot button" 
  on the ESP32 while you powering up (connecting the USB cable) the Microcontroller.
  You can also Press the "Boot button" hold it down and Press "Reset" then Release the 
  Boot button. The Microcontroller can change USB-Serial Port so check the active Port.
  The Erase part can take some minutes to finish.   
  
  Installation:
  1. Connect the Microcontroller with a "real" USB-cable (not a charging cable) to the USB port. 
  2. Select the WICS Board from the menu/submwenu and click the "Connect" button.
  3. Follow the instructions on the screen.
  4. When done, Reboot the Microcontroller.
  5. Upload your configuration file (using ESP-Connect).
