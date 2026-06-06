# WICS-Install
Installation of nowRail and WICS add-on to ESP32 Microcontroller
---
- Installation of nowRail and WICS software delete existing content on the Microcontroller.
- If upgrading the software? Please copy existing configuration files first from littleFS.
- Only Install the software if you have the associated WICS Board (MCU & PIN dependent).
- If you get problem with "hanging or installation not starting" please set 
  the Microcontroller into "Flash Mode" by holding down the right Boot button 
  while you powering up (connecting the USB cable) the Microcontroller.
  
  Installation:
  1. Select the WICS Board from the menu and click the "Connect" button.
  2. Follow the instructions on the screen.
  3. When done, Reboot the Microsontroller.
  4. Upload your configuration files.
## 🚀 How to Flash the Firmware (ESP32-S3)

Due to a known compatibility bug with the standard ESP Web Tools and the ESP32-S3 chip architecture, we use the stable and reliable **Spacehuhn ESPWebTool** for this board. 

Follow these simple steps to flash your device using Google Chrome or Microsoft Edge:

### 1. Download the Firmware
* Download the latest sammanslagen binary file here: 

### 2. Put your XIAO ESP32-S3 into Bootloader Mode
To allow the web browser to flash the chip, you must force it into its hardware bootloader mode:
1. **Unplug** the USB cable from your XIAO board.
2. Press and hold down the **BOOT button** (this is the **LEFT** button next to the USB-C port).
3. While keeping the BOOT button pressed, **plug the USB cable back into your computer**.
4. Release the **BOOT button**. 
*(The board's LED will stay dim or off, which means it is successfully waiting for a new firmware).*

### 3. Flash the Chip via Browser
1. Open the installation tool in a new tab: https://esptool.spacehuhn.com/
2. 2. Click the big **Connect** button on the page.
3. A popup will appear in your web browser. Select your device's COM port from the list and click **Connect**.
4. In the first file row, change the address box manually to **`0x0`** (or just `0`).
5. Click **Choose File** on that same row and select your downloaded `firmware_pca.bin`.
6. Leave any other address rows empty.
7. Click the **Program** button at the bottom.

Wait for the terminal counter to reach **100%**. Once completed, press the **RESET button** (the RIGHT button next to the USB port) or unplug and replug the USB cable to start your newly installed software!
