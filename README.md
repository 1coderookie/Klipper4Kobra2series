# Klipper4Kobra2series
This is a collection of `klipper.bin` and `printer.cfg` files for Anycubic Kobra 2 series models (if there are any available).  
Currently it's **not** possible to flash a native Klipper to the Kobra 2 Pro/Plus/Max onto the stock mainboard, so you won't find any files here yet. If it'll ever be possible and I come across working solutions, I'll add them here as well.  

Please mind that *I didn't create the files which are being offered here* - I just reached out to people I came across who offered their files somewhere and asked if they'd be willing to upload their files here as well, so that it'll be easier to find them.  
*So if you have any questions about specific files or configurations, please don't reach out to me - reach out to the specific author/contributor instead!* 
 
However, before reaching out, please refer to the [official Klipper documentation](https://www.klipper3d.org/) and try to solve the problem on your own. 

---

**Installation and Configuration**  
Please refer to the [official Klipper documentation about how to install and configure Klipper](https://www.klipper3d.org/Installation.html) in the first place for an extensive description about how to install and configure Klipper!  
(Note: at those docs there's OctoPrint being mentioned - you don't need to have that one installed though!)  

Basically, for flashing your machine with Klipper firmware, you need to rename the file `klipper.bin` to `firmware.bin` and put the file into the root directory of your microSD card. It's advisable to not have any other files on the card.  
Then put the card in the machine's cardreader and switch it on.  
The machine will then enter the flashing mode - sometimes there'll be a message shown at the display of the control unit like "Upating firmware...", sometimes the screen will just stay black.  
However, as the displays of the stock control units don't work with Klipper, just leave it sit for about 5-10 minutes until you switch it off.  
Then remove the card, connect the printer to the host which is running Klipper (e.g. a Raspberry Pi) via USB and switch it on again.  

Then you need to determine the specific serial port of the host where the printer is connected to and set that in the `printer.cfg` file.  
As soon as you have done this correct, you should be able to connect to the printer already though the UI of your frontend (e.g. Mainsail, Fluidd).  

Once you're able to do so, continue with the [configuration checks](https://www.klipper3d.org/Config_checks.html).  
*Don't skip this step and try to start printing right away as you might end up harming the machine if any configuration is somewhat wrong!*  
