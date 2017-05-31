# factory-image-flash-tool
Package with tools to flash 64-bit LOLLIPOP factory images on YUPHORIA

## How to
### Steps to flash factory image
 1. Install fastboot in your system. 
      (<code>sudo apt install android-tools-fastboot</code> for Ubuntu)
      
 2. Download the LOLLIPOP factory image fastboot package for YU YUPHORIA from [Here](https://cyngn.com/support/)

 3. Extract the contents of the fastboot package into a folder.

 4. Download flash_all.sh from this repo.

 5. Copy the flash_all.sh into the same folder    
    To make sure, check that system.img, boot.img etc files are in the same
    folder as flash_all.sh.

 6. Connect your phone in fastboot mode, steps for which are : -   
  a. Power off your phone    
  b. Press and hold the Volume Up key    
  c. With the Volume Up key, connect the phone to your PC/Laptop with USB cable   
  d. You can let go off the Volume Up key when Fastboot Mode is displayed on the screen    

 7. Run flash_all.sh in terminal (as root). The flashing process will start normally.
      (in terminal <code>cd</code> to the folder and do <code>sudo ./flash_all.sh</code>)

 8. <b>DO NOT</b> disconnect the device during flashing procedure!

 9. You'll see a completion message when the flashing process is over.

 10. The phone will automatically reboot once the flashing process is over, Disconnect the USB.

#### 3rd Party Licenses

The adb and fastboot tools are distributed by Google, as part of Android SDK. 
There are licensed under Apache 2.0 by Google, and can be redistributed under 
a compatible license. 
