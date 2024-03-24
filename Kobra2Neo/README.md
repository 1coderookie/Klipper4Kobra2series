# Files for the KOBRA 2 NEO
Here you'll find an example `printer.cfg` file for the **Kobra 2 Neo**.  
 
*Thanks to @[AJolly](https://github.com/AJolly) for contributing the specific files!*  

If you have questions about the specific files, please reach out to the contributor directly or (if you somehow can't) open an issue here where you then mention the contributor, so that he gets a notification.  
*Please* ***don't*** *reach out to me personally as I didn't create the files!*  
Thanks. 

---

If you own a **Kobra 2 Neo**, you might want to check out my comprehensive infosite about it: [Kobra2Neo Insights](https://1coderookie.github.io/Kobra2NeoInsights/)  
You'll find many specific information as well as some general kind of information.  

There's also a [specific chapter about Klipper](https://1coderookie.github.io/Kobra2NeoInsights/firmware/fw_klipper/) you might want to check out.  

---

## Disclaimer  

***USE AT YOUR OWN RISK!***  

**I'm not responsible in any way if your machine somehow gets harmed or if any problems occur when using any of the files which are being offered here!**  


---

## Installation and Configuration  

***ATTENTION!***
***These files are specifically made for the Kobra 2 Neo - you can't use them with any other printer model!***

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

---

***If you like this work, please consider starring and supporting it.***  

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

