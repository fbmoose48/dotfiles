#jailbreak for Apple devices running iOS 12-13
#Checkra1n 0.9.8.1 beta (x86_64)

1. Connect your iDevice

2. Type “lsusb” to check if your iDevice is recognized.
The USB ID displayed should be “05ac:12a8“.

3. Put your iDevice into DFU (Device Firmware Upgrade) mode.
For A10 devices (iPhone 7 and iPhone 7 Plus, iPad 2018, iPod touch 7):
-Hold down both the Side button and Volume Down button.
-After 8 seconds, release the Side button while continuing to hold down the Volume Down button. 
-If the Apple logo appears, the Side button was held down for too long.
-Nothing will be displayed on the screen when the device is in DFU mode. If open, iTunes will alert you that a device was detected in recovery mode. 

4. Check whether your iDevice is still recognized with “lsusb“.
The USB ID displayed should now be “05ac:1227“.

5. Run checkra1n in CLI mode using the command “sudo ./checkra1n -c“.

6. Your iDevice should now be jailbroken.
However, the method is not entirely reliable, so you may need to retry the steps to achieve success.

