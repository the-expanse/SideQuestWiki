Having connection issues?
First thing to try is making sure you have done every one of the 6 [Setup Steps](https://sidequestvr.com/#/setup-howto)
after that would be to try a different cord. If you have a phone USB cable that fits use that. Also try a different USB port. This solves 90% of problems with ADB connection issues, if your using Bluestacks, a Wifi Extender or a VPN best to refrain from them as they are all known to cause issues for SideQuest, always try to connect directly to the same router as your pc or phone, to minimize issues with Beat On and Beatsaber just install and manage songs in headset to avoid issues with Those two applications specifically 



Make sure Sidequest is open before proceeding 
=====================
<!--This next bit will be tricky so make sure to only do it if no other options available work

if you're still having issues with ADB try the below

[Entire ADB folder](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)

Just unzip this, then in sidequest head to settings and click open main app folder
then look for the same folder (Platform tools) and go into it, copy and paste all the files and folders from this into it and click replace all, then reboot sidequest.-->




For Windows 
You have to open `cmd` or Command Prompt. 
( If your on mac then click the wrench icon in the top right and click "open adb folder" - then drag this onto a terminal window )

Type this `cd %appdata%\SideQuest\platform-tools\`<br>
Then type this `adb devices`<br>

You should see:
```
List of devices attached
1SOTGDHHSD93  device
```

If you see `1SOTGDHHSD93  unauthorized` - put on your headset now you should see the message to allow usb debugging - click always allow. 

if you see  `1SOTGDHHSD93  offline` - then type `adb kill-server` and then `adb devices` again.

if you see `cannot connect to daemon` then open up task manager and kill the `adb.exe` process - `taskkill /f /im adb.exe`





Mac 
Open Terminal 

then type in
`cd "~/Library/Application Support/SideQuest/platform-tools"`
(The quotes are required)

Then type 
`./adb`

You should now see something similar to the following:

`List of devices attached
1SOT********  device`

If you see unauthorized, then you need to put on your headset while it's still connected to your computer and choose `Always Allow`
This will inform the headset that connections to your computer are okay and allow it to connect properly.

If you see offline
then type 
`adb kill-server`
and then 
`adb devices`


If you see a message about not being able to connect to daemon or similar language, then:

For Mac: Run 
`pkill adb `
in Terminal.

after that you can then attempt to restart Sidequest to see if you are properly connected, 
it might take a moment but it should connect properly now.