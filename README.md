# Firmware

A Marlin 2.0.9.6 firmware I made for the Ender 3 Max printer with STM32F103RE Creality 4.2.2(512K) board. 

This firmware supports Host Actions options and M73 reporting. 

This is a test to see if this firmware will allow for stopping and starting prints through Octoprint, and to see if it will display print status on the LCD when printing a model from the web interface of Octoprint. 

Download the Marlin source code at: https://marlinfw.org/meta/download/

More updates to come :)

# Installation
 1. Download your preferred .bin file and the DWIN_SET and private folders from the LCD Updates folder. 
 2. Format SD card with 4096 allocation.
 3. Put the DWIN_SET and private folders on the root of the SD card (make sure ONLY these folders are on the card or the flash may fail!)
 4. Eject the SD card, power down your printer, and insert the SD card in to the LCD screen (you may have to take the screen apart, it is just 4 screws and then the screen pops off giving you access to the SD card reader on the board)
 5. Power on your printer and wait for the update to complete. The screen should show progress, and it should say flash complete when it finishes. 
 6. Power down the printer and remove the SD card, bring it back to your computer. 
 7. Format the card again to be safe, and then put the .bin file on the root of the SD card. 
 8. Insert SD card into printer and power on. Update should take 15-20 seconds and then you will be in the main menu!

To Do: Build the firmware for the 2.1.x bugfix release of Marlin

<ins>***Updates***</ins>

  **5/27/23:**
  Added LCD files and readme from TH3D Unified Firmware. Flashing the .bin alone may cause your display to not work. 
  
  
  **5/26/23:**
    
   Was looking through advanced config file and stumbled across some games. The new bin file Ender3Max4.2.2Games is the same firmware just with the games added in. 
     
   Games will be found under About menu option.
    
   *As far as I know the games will only work with printers that have a non-touch screen with a knob. Have not had the chance to test just yet if this will work with touch screen printers. Stay tuned!*
   
   #Credits
   TH3D for the LCD files required to make the firmware work! https://github.com/th3dstudio/UnifiedFirmware
       
