Having connection issues? First things to try
---

The simple things to check are

ALL the setup steps
---

Making sure you have done every one of the 6 
[Setup Steps](https://sidequestvr.com/#/setup-howto) 


A different cord
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609880483286876218/Screenshot_1163.png)

make sure to abstain from using the code the Quest came with as it is not the best quality and is quite faulty for anything save charging your device, If you have a phone USB cable that fits use that, Also try a different USB port.


NO VPN
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609881862956908564/Screenshot_1164.png)

if your it, using Bluestacks, NOX or a Wifi Extenders of any kind can lead to problems as well, so be sure to disable VPN services of any kind when using SideQuest, best to refrain from them as they are all known to cause issues for SideQuest

## [How to properly uninstalling BlueStacks](https://github.com/the-expanse/SideQuest/wiki/BlueStacks-is-causing-issues,-how-do-i-remove-it)

Antivirus systems
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609882817962442752/Screenshot_1165.png)

Antivirus applications such as AVG, Avast or similar programs can cause issues so try to check if ADB.exe is running, if not see it it has been Quarantined/Vaulted by it and tell your antivirus to allow it through.


Android Emulators
----

The use of Android Emulators cause issues if it is being detected first, so make sure it is turned off completely and not running in task manager, as well as have it not set to "start on boot" in your Computer settings.


Your Router
----

Always try to connect directly to the same router as your PC or phone, to minimize issues with Beat On and Beatsaber just install and manage songs in headset to avoid issues with Those two applications specifically 

If you are having issues with Beat On Only
----

1. Try to update Beat On first, just search "Beat On" in the mods category, click "open" and click "install latest" as usual. Then re-enable BeatOn from the Beat On icon at the top of SideQuest.

2. If the above doesn't work for Beat On try to ping your headset,just Check [HERE](https://www.lifewire.com/how-to-ping-computer-or-website-818405) for how to ping your headset, Then go [HERE](https://www.makeuseof.com/tag/7-simple-steps-diagnose-network-problem/) for information on troubleshooting general network problems.


If all the things above fail to assist you then try the below.

Make sure SideQuest is open before proceeding 
=====================
<!--This next bit will be tricky so make sure to only do it if no other options available work

if you're still having issues with ADB try the below

[Entire ADB folder](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)

Just unzip this, then in sidequest head to settings and click open main app folder
then look for the same folder (Platform tools) and go into it, copy and paste all the files and folders from this into it and click replace all, then reboot sidequest.-->



(Windows)
----
Open `Command Prompt`

![](https://cdn.discordapp.com/attachments/608376262347587595/609878697540976827/Screenshot_1162.png)

In the window type `adb disconnect` and hit enter, then close SideQuest unplug then plug your device back in and reopen SideQuest.

### Mac
----

Open Terminal and type `./adb disconnect` then closing SideQuest, unplug then plug your device back in and reopen SideQuest to connect.


if all of that fails to assist attempt the below


### Windows
You have to open `cmd` or Command Prompt. 

(If your on mac then click the wrench icon in the top right and click "open adb folder" - then drag this onto a terminal window )

Type this

`cd %appdata%\SideQuest\platform-tools\`<br>

Then type this

`adb devices`<br>

You should see:
```
List of devices attached
1SOTGDHHSXXX  device
```

If you see something like 

`1SOTGDHHSXXX  unauthorized`

Put on your headset now you should see the message to allow USB debugging - click always allow. 

If you see something like 

`1SOTGDHHSXXX  offline`

Type `adb kill-server` and then `adb devices` again.

If you see

`cannot connect to daemon`

Open up task manager and kill the `adb.exe` process with `taskkill /f /im adb.exe`





### Mac 
Open terminal and type in

`cd "~/Library/Application Support/SideQuest/platform-tools"`
(The quotes are required)

Then type `./adb` you should now see something similar to the following:

```List of devices attached

1SOT********  device
```

If you see unauthorized, then you need to put on your headset while it's still connected to your computer and choose `Always Allow`
This will inform the headset that connections to your computer are okay and allow it to connect properly.

If you see offline then type 

`adb kill-server`

and then 

`adb devices`


If you see a message about not being able to connect to daemon or similar language, then:

### Mac
Run `pkill adb ` in terminal.

After that you can then attempt to restart SideQuest to see if you are properly connected, it might take a moment but it should connect properly now.