# Maverick Storm 1 Hybrid

## Software Versions

[V1.240103 - Maverick Storm 1 Hybrid](https://github.com/Chauvet-Pro/MAVERICKSTORM1HYBRID/blob/24eb36d7b53355e77e9dc43432010ccb0c58a063/firmware/V1.240103.zip)
- Added Sky Tracker mode
- Fixed IGMP subscription issue
 
[V1.231128 – Maverick Storm 1 Hybrid](https://github.com/Chauvet-Pro/MAVERICKSTORM1HYBRID/blob/8841b0bb5735971ce0528bb9519e0385254d9f04/firmware/V1.231128.zip)
-	Added pan/tilt power release
  
[V1.230731 – Maverick Storm 1 Hybrid](https://github.com/Chauvet-Pro/MAVERICKSTORM1HYBRID/blob/5899ceda5837c5f333ccd4402ca39ae2922c1e4e/firmware/V1.230731.zip)
-	Fixed RDM issues

&nbsp; 

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **<YES>**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **<UP>** or **<DOWN>** to select the desired version.  Press **<ENTER>**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **<YES>**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
 
