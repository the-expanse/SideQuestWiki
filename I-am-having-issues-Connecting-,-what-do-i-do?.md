Having connection issues? First things to try
---

The simple things to check are

1. Making sure you have done every one of the 6 [Setup Steps](https://sidequestvr.com/#/setup-howto) 


2. A different cord, make sure to abstain from using the code the Quest came with as it is not the best quality and is quite faulty for anything save charging your device, If you have a phone USB cable that fits use that, Also try a different USB port.


3. NO VPN, if your using Bluestacks, NOX, a Wifi Extender or a VPN of any kind best to refrain from them as they are all known to cause issues for SideQuest


4. Antivirus such as AVG, Avast or something similar cause issues so try to check if ADB.exe is running, if not see it it has been quarantined by it and tell your antivirus to allow it through.


5. The use of Android Emulators cause issues if it is being detected first, so make sure it is turned off completely and not running in task manager, as well as have it not set to "start on boot" in your Computer settings.


6. Always try to connect directly to the same router as your pc or phone, to minimize issues with Beat On and Beatsaber just install and manage songs in headset to avoid issues with Those two applications specifically 

If you are having issues with Beat On Only
----

1. Try to update Beat On first, just search "Beat On" in the mods category, click "open" and click "install latest" as usual. Then re-enable BeatOn from the Beat On icon at the top of SideQuest.

2. If the above doesnt work for Beat On try to ping your headset,just Check [HERE](https://www.lifewire.com/how-to-ping-computer-or-website-818405) for how to ping your headset, Then go [HERE](https://www.makeuseof.com/tag/7-simple-steps-diagnose-network-problem/) for information on troubleshooting general network problems.


If all the things above fail to assist you then try the below.

Make sure Sidequest is open before proceeding 
=====================
<!--This next bit will be tricky so make sure to only do it if no other options available work

if you're still having issues with ADB try the below

[Entire ADB folder](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)

Just unzip this, then in sidequest head to settings and click open main app folder
then look for the same folder (Platform tools) and go into it, copy and paste all the files and folders from this into it and click replace all, then reboot sidequest.-->



(Windows)
----
Try to open `Command Prompt`

![](https://cdn.discordapp.com/attachments/608376262347587595/609878697540976827/Screenshot_1162.png)

and in the window try typing `adb disconnect` and hit enter, then close SideQuest replug your device and reopen SideQuest.

Mac
----

Try to open Terminal and try typing `./adb disconnect` then closing SideQuest, replug your device and reopen SideQuest to connect.


if all of that fails to assist attempt the below


For Windows 
You have to open `cmd` or Command Prompt. 
( If your on mac then click the wrench icon in the top right and click "open adb folder" - then drag this onto a terminal window )

Type this
`cd %appdata%\SideQuest\platform-tools\`<br>
Then type this
`adb devices`<br>

You should see:
```
List of devices attached
1SOTGDHHSXXX  device
```

if you see something like 
`1SOTGDHHSXXX  unauthorized` 
- put on your headset now you should see the message to allow usb debugging - click always allow. 

if you see something like 
`1SOTGDHHSXXX  offline`

- then type `adb kill-server` and then `adb devices` again.

if you see
`cannot connect to daemon`
then open up task manager and kill the
`adb.exe`
Process - `taskkill /f /im adb.exe`





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