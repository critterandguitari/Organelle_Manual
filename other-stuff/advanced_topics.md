#Advanced Topics

#####New USB Drive:  
1.	Insert your USB Drive into your computer. You may have to use a disk utility to reformat the USB disk to FAT filesystem if it is not already in this format. 

2.	Download the C&G Organelle patches [here](https://github.com/critterandguitari/Organelle_Patches/archive/master.zip).

3.	Unzip the file and rename folder `Patches` (case sensitive).  

4.	Copy `Patches` to the root directory of drive. For example, the 'Analog Style' patch would be located like this: `/YourUSBdrive/Patches/Analog Style`  

5.	Eject drive from your computer
Insert drive in Organelle and select `Reload` from `Storage` menu.
  
#####New SD Card  
1.	Download the [microSD card disk image](http://thepeacetreaty.org/organelle/diskimages/20180529-v3.1.img.zip) to your computer.   

2.	Download [Etcher](https://etcher.io/) to your computer to burn the OS on to the SD card.

3.	Power down the Organelle. 

4.	Locate the thin slit in the rear of the enclosure (above 'Critter'). Use a pin or paperclip to press in on the black SD card to eject it and it will spring out gently.  

5.	Insert the microSD card into your computer (you may need an adapter).

6.	Use the Etcher program to burn the OS on to the SD Card. Be sure to unzip the disk image before burning. Although Etcher says it can burn from a zip, we have have trouble doing so.  

7.	After Etcher is finished, remove the microSD card from your computer and reinsert in Organelle. Make sure it does not fall in the enclosure. You may want to flip the Organelle upside down. You will have to use the same pin/paperclip to press it in until you hear/feel a 'click.'  

8.	Restart the Organelle. 

#####Creating .zop  

#####User-defined Scripts (what is inside 'Extras' in menu)  

#####Partioning the SD Card (running patches from SD, not USB)
Some users may want store patches on the SD Card rather than the USB drive since it frees up up a USB port. This is possible with a little work.  

There are a few things to consider before doing away with your USB drive:
  
-	You will be locking yourself into using WiFi for updating your Organelle with new patches. The SD card partition is a format that other operating systems (Mac OS, Windows) cannot read - so you just can't pop your SD card into your computer as you would a USB drive.  
-	Early production models shipped with 4GB SD cards as this size was adequate for storing the Organelle's OS. If your Organelle has this size SD card, you will have to swap it out for a larger one (8GB or more). You will need to follow the steps above for setting up a new SD card. 

If you are cool with those caveats, here are the steps:  
(*list steps here: 1. make sure your SD card is 8GB or bigger - if not, see caveat #2 2. Download the patch for resizing.....*)  
  
At this point, the Storage menu commands like Reload will affect your SD card. 

#####Using Remote Viewing   

VNC (Virtual Network Computing) allows for remote patching between Organelle and another computer, ie., using another computer to access patches on Organelle for editing. To configure VNC on your Organlle:

1.	Download TigerVNC for Organelle [here](https://patchstorage.com/tigervnc/).
2. Put the .zop file in the USB drive in `Patches`.
3. Reload, and scroll to `Install TigerVNC` in the patch list (it will fall under the T's, not the I's). This will run the install. Once completed, Mother will restart.
4. Go to `Settings`, `WiFi Setup`, make sure WiFi is tunred on, and join your WiFi network, or select `Start AP`.
5. If you selected `Start AP`, join that network on your computer.
6. Return to the `System` menu and navigate to `Extras` > `TigerVNC`. 
7. If you are using a Mac:
	-	Open the Screen Sharing app.
	- 	In 'Connect To' enter `organelle.local:5901` and press Return.
	-  When prompted for a password, enter __coolmusic__.
	-  After a moment, a display will pop up that visualizes Organelle's OS, which means you're in!

8.	If you are using a PC:
	-	Install RealVNC or TightVNC
	-	Connect to `organelle.local:5901`.
	-	When prompted for a password, enter __coolmusic__.
	-  After a moment, a display will pop up that visualizes Organelle's OS, which means you're in!

For more information on configuring VNC with Organelle, see [this forum post](https://forum.critterandguitari.com/t/remote-patching-using-vnc/3607).

#####Compiling Externals

#### SerialOSC

Connect an external instrument. This idea has been explored in [this thread](https://forum.critterandguitari.com/t/serialosc-monome-with-organelle/233).
