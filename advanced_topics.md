#Advanced Topics

#####New USB Drive:  
Insert your USB Drive into your computer. You may have to use a disk utility to reformat the USB disk to FAT filesystem if it is not already in this format. 

Download the C&G Organelle patches from here: https://github.com/critterandguitari/Organelle_Patches/archive/master.zip  

Unzip the file and rename folder `Patches` (case sensitive).  

Copy `Patches` to the root directory of drive. For example, the 'Analog Style' patch would be located like this: `/YourUSBdrive/Patches/Analog Style`  

Eject drive from your computer
Insert drive in Organelle and select `Reload` from `Storage` menu.
  
#####New SD Card  
Download the microSD card disk image to your computer: http://thepeacetreaty.org/organelle/diskimages/20180529-v3.1.img.zip  

Download this program to your computer to burn the OS on to the SD card:  https://etcher.io/  

Power down the Organelle  

Locate the thin slit in the rear of the enclosure (above 'Critter'). Use a pin or paperclip to press in on the black SD card to eject it and it will spring out gently.  

Insert microSD into your computer (you may need an adapter)  

Use the Etcher program to burn the OS on to the SD Card. Be sure to unzip the disk image before burning. Although Etcher says it can burn from a zip, we have have trouble doing so.  

After Etcher is finished, remove the microSD card from your computer and reinsert it in Organelle. Make sure it does not fall in the enclosure. You may want to flip the Organelle upside down. You will have to use the same pin/paperclip to press it in until you hear/feel a 'click.'  

Restart the Organelle

#####Creating .zop  

#####User-defined Scripts (what is inside 'Extras' in menu)  

#####Partioning the SD Card (running patches from SD, not USB)
Some users may want store patches on the SD Card rather than the USB drive since it frees up up a USB port. This is possible with a little work.  

There are a few things to consider before doing away with your USB drive:  
1. You will be locking yourself into using WiFi for updating your Organelle with new patches. The SD card partition is a format that other operating systems (mac OS, windows) cannot read - so you just can't pop your SD card into your computer as you would a USB drive.  
2. Early production models shipped with 4GB SD cards as this size was adequate for storing the Organelle's OS. If your Organelle has this size SD card, you will have to swap it out for a larger one (8GB or more). You will need to follow the steps above for setting up a new SD card. 

If you are cool with those caveats, here are the steps:  
(*list steps here: 1. make sure your SD card is 8GB or bigger - if not, see caveat #2 2. Download the patch for resizing.....*)  
  
At this point, the Storage menu commands like Reload will affect your SD card. 

#####Using Remote Viewing   
first, follow steps to Partion the SD card since TigerVNC does not like to be run from USB drive.  

#####Compiling Externals
