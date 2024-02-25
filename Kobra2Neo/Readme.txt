How to install
A guide by Xenyonmedia


DISCLAIMER:
I am NOT taking any responsibility for any damages at all under any circumstance. 
You do this on your own risk. 


If you are unfamiliar with klipper and Raspberrys, watch the first part of this video https://www.youtube.com/watch?v=MK0-MDVJG94

After you have installed klipper and mainsail/fluidd on your pi, upload the configuration and "makro" file to the raspberry in the machine tab.

Flash the printer by using an SD card.
1. Format SD with 4096 bytes with fat32 (the partition on the sd card may not be larger than 7.6gb) and put the firmware.bin on the card.
2. Shut down the printer and wait until it is completely off.
3. Plug in the sd card
4. Turn the printer on and wait 60 seconds. The screen will show something along the lines of "Software Update..."
5. Shut down the printer and wait until it is completely off.
6. Turn it back on and connect it to your pi.


Restart klipper and the printer should connect. If not you can always flash back the original software with the firmware.bin in the Marlin folder of my ZIP.



Going back to original software:
Flash with instructions above with marlin bin.