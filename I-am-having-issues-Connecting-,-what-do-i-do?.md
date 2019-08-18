Having connection issues? First things to try
---

The simple things to check are


The main setup steps for installing SideQuest
---

Making sure you have done every one of the 6 
[Setup Steps](https://sidequestvr.com/#/setup-howto) 


Re:Toggle Dev mode
----

Some times something goes awry when you initially set things up, or after trying the steps more then once, so in your Oculus Application in your phone, try to disable, then re enable Developer mode in settings while your phone is connected Via Bluetooth to your Headset


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




![](https://cdn.discordapp.com/attachments/608376262347587595/609878697540976827/Screenshot_1162.png)


***Windows***: Open `cmd` or Command Prompt. `cd %appdata%\SideQuest\platform-tools\`

***Mac***: Open terminal and type in `cd "~/Library/Application Support/SideQuest/platform-tools"`



***Windows***: Type `adb disconnect`.

***Mac***: Type `./adb disconnect`.

Then type

***Windows***: `adb devices`

***Mac***: `./adb devices`

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

If you see `cannot connect to daemon` or similar

***Windows***: Open up task manager and kill the `adb.exe` process or in cmd with `taskkill /f /im adb.exe`

***Mac***: Run `pkill adb ` in terminal.