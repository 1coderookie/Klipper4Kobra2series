# Klipper4Kobra2series
This is a collection of example `printer.cfg` files for Anycubic Kobra 2 series models (if there are any available).  

Please mind that *I didn't create all the files which are being offered here* - I just reached out to people I came across who offered their files somewhere and asked if they'd be willing to upload their files here as well, so that it'll be easier to find them.  
*So if you have any questions about specific files or configurations, please don't reach out to me - reach out to the specific author/contributor instead!*  
 
However, before reaching out, please refer to the [official Klipper documentation](https://www.klipper3d.org/) and try to solve the problem on your own. 

---

**If you didn't come across them yet, please see my comprehensive infosites about various Anycubic FDM printers:**  
- [Kobra 2 Insights](https://1coderookie.github.io/Kobra2Insights/)  
- [Kobra 2 Neo Insights](https://1coderookie.github.io/Kobra2NeoInsights/)  
- [Kobra 2 Pro Insights](https://1coderookie.github.io/Kobra2ProInsights/)  
- [Kobra 2 Plus Insights](https://1coderookie.github.io/Kobra2PlusInsights/)  
- [Kobra 2 Max Insights](https://1coderookie.github.io/Kobra2MaxInsights/)  

---

## Disclaimer  

***USE AT YOUR OWN RISK!***  

**I'm not responsible in any way if your machine somehow gets harmed or if any problems occur when using any of the files which are being offered here!**  

---

## Installation and Configuration  

**Please refer to the [official Klipper documentation about how to install and configure Klipper](https://www.klipper3d.org/Installation.html) in the first place for an extensive description about how to install and configure Klipper!**  

Generally speaking, as a rough guide for the *Kobra 2* and *Kobra 2 Neo* where the stock mainboard can be flashed with a native Klipper, you need to rename the file `klipper.bin` to `firmware.bin` and put the file into the root directory of your microSD card. It's advisable to not have any other files on the card.  
Then put the card in the machine's cardreader and switch it on.  
The machine will then enter the flashing mode - sometimes there'll be a message shown at the display of the control unit like "Upating firmware...", sometimes the screen will just stay black.  
However, as the displays of the stock control units don't work with Klipper, just leave it sit for about 5-10 minutes until you switch it off.  
Then remove the card, connect the printer to the host which is running Klipper (e.g. a Raspberry Pi) via USB and switch it on again.  
*Again: mind that this is how it's being done at the Kobra 2 and Kobra 2 Neo where one wants to flash the stock mainboard. This doesn't work at the Kobra 2 Pro/Plus/Max though, see the according sections at the respective infosites.*   

Then you need to determine the specific serial port of the host where the printer is connected to and set that in the `printer.cfg` file.  
As soon as you have done this correct, you should be able to connect to the printer already though the UI of your frontend (e.g. Mainsail, Fluidd).  

Once you're able to do so, continue with the [configuration checks](https://www.klipper3d.org/Config_checks.html).  
*Don't skip this step and try to start printing right away as you might end up harming the machine if any configuration is somewhat wrong!*  

---

***If you like this work, please consider starring and supporting it.***  

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

