# Having connection issues? First things to try


If you are having issues with Beat On Only
----

1. Try to update Beat On first, just search "Beat On" in the mods category, click "open" and click "install latest" as usual. Then re-enable BeatOn from the Beat On icon at the top of SideQuest.

2. If the above doesn't work for Beat On try to ping your headset,just Check [HERE](https://www.lifewire.com/how-to-ping-computer-or-website-818405) for how to ping your headset, Then go [HERE](https://www.makeuseof.com/tag/7-simple-steps-diagnose-network-problem/) for information on troubleshooting general network problems.


if not, the most common things to check are

Re:Toggle Dev mode
----

Some times we forget we disabled it for some reason, always good to check, also very rarely there is a glitch causing somthing to goes awry when you initially set things up, after trying the install steps more then once, or reinstalling or updating SideQuest so in your Oculus Application in your phone try to dis and re enable it, if you turn it off and you suddenly connect it is an error with the application thinking on is of and off is on, to fix this just switch Dev mode to to disabled, turn your headset off, switch Dev mode to on, then re boot your headset while phone is connected Via Bluetooth to your Quest.

The main setup steps for installing SideQuest
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

## [How to properly uninstall BlueStacks](https://github.com/the-expanse/SideQuest/wiki/BlueStacks-is-causing-issues,-how-do-i-remove-it)

Antivirus systems
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609882817962442752/Screenshot_1165.png)

Antivirus applications such as AVG, Avast, BitDefender or similar programs can cause issues so try to check if ADB.exe is running, if not see it it has been Quarantined/Vaulted by it and tell your antivirus to allow it through, if you do not know how to do this search google for "how to allow a program through quarantine" for your spastic Anti Virus, if it is windows defender, search it for windwos defender


Android Emulators
----

The use of Android Emulators cause issues if it is being detected first, so make sure it is turned off completely and not running in task manager, as well as have it not set to "start on boot" in your Computer settings.


Your Router
----

Always try to connect directly to the same router as your PC or phone, to minimize issues with Beat On and Beatsaber just install and manage songs in headset to avoid issues with Those two applications specifically 


If all the things above fail to assist you then try the below.

### Make sure SideQuest is open before proceeding

How-To use commands to force boot or reset ADB for connection (Windows or Mac)
=====================


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

Failing the above 
----

This is only for windows, Also make sure to only do it if no other options available work and if you are still having issues with ADB try the below

Install the below Folder

[Entire ADB folder](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)

then proceed to unzip it,
if you do not know how to, check google for how to unzip a folder for your version of windows,
then in SideQuest head to settings
Then at the top of the page click `Open Main App` folder and proceed to look for the (Platform tools) Folder
Open it, make sure to close SideQuest, then delete everything in that folder before you then copy and paste all the files and folders from the installed unzipped folder into it and click replace all, when finished  reboot SideQuest and try once more.