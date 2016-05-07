# WhatsApp-Key-DB-Extractor
Allows WhatsApp users to extract their cipher key and databases on non-rooted Android devices.


# PREREQUISITES:

 1.) O/S: Windows Vista, Windows 7, Windows 8, Windows 10 or Linux
 
 2.) Java - If not installed: https://www.java.com/en/download/
 
 3.) ADB (Android Debug Bridge) Drivers
 
 4.) USB Debugging must be enabled on the target device. Settings -> Developer Options -> (Debugging) USB debugging
     If you cannot find Developer Options then please go to: Settings -> About phone/device and tap the Build number
     multiple times until you're finally declared a developer.
     
 5.) Android device with Android 4.0 or higher. I.E. Ice Cream Sandwich, Jelly Bean, KitKat, Lollipop or Marshmallow.



# INSTRUCTIONS:

 1.) Extract the master zip file on your computer maintaining the directory structure.
 
 2.) Click on "WhatsAppKeyDBExtract.bat" (Windows) or "WhatsAppKeyDBExtract.sh" (Linux).
 
 3.) Connect your device via USB, unlock your screen and wait for "Full backup" to appear.
 
 4.) Enter your backup password or leave blank (if none set) and tap on "Back up my data".
 
 5.) Confirm backup password in your command console and then check your "extracted" folder.
 


# TROUBLESHOOTING:

 1.) If you have never used USB Debugging before, you may also need to verify the fingerprint.
 
 2.) If you have set a default backup password in your Android settings, then this MUST be the
     backup password that you PROVIDE when prompted to backup your data. Else it WILL fail!
     
 3.) Linux users may need to set the script permissions as executable. Depending on the adb
     permissions, you may also need to "sudo ./WhatsAppKeyDBExtract.sh" from your command console.
     
 4.) If you're having issues with "WhatsAppKeyDBExtract.bat" then right click "WhatsAppKeyDBExtract.ps1"
     and select "Run with PowerShell". You may have to enter "y" at first run for execution policy.
     
     
     
     
     
     AUTHOR: TripCode
     THANKS: dragomerlin for Android Backup Extractor and Abinash Bishoyi for being cool.