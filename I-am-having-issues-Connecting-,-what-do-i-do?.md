## [Supported Devices](https://github.com/the-expanse/SideQuest/wiki/Supported-Devices)

## Having issues?
If not seeing green dot and the phrase (Connected) top left inside SideQuest and instead finding it to be a yellow dot, or have multiple devices connected but are unable to connect your Quest properly to install for some reason try to enable wireless mode before disconnecting your headset prior to installation, if you are in Wireless mode and it should resolve most issues else try the solutions below.

#### First things to try

Note that all information below is not error specific as some errors share Solutions so be sure to try everything and look into each one at least once.

Make sure you have installed the very latest SideQuest from [SideQuestVR.com](https://sidequestvr.com/#/download) properly before proceeding.
Also double check the main setup steps for installing SideQuest to make sure you have done every one of the 5 [mandatory setup steps](https://github.com/the-expanse/SideQuest/wiki/SideQuest-Setup-&-How-To-install#step-1-install-sidequest-to-your-computer).
Some times you need to reset Developer mode in your phone app for connection issues, for that issue see #3 on this list.

# [Setup Steps](https://sidequestvr.com/#/setup-howto) 

For Windows users be sure to double check step 3 to make sure the drivers were properly installed

For Windows 7 users
----

Windows 7 is an older OS and requires manual installation of drivers so see this link for driver installation instructions.

https://github.com/the-expanse/SideQuest/wiki/I-Have-Windows-7,-can-i-use-SideQuest%3F



----
# 1 Your Cord
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609880483286876218/Screenshot_1163.png)

Make sure to try a few different ones and to abstain from using the cord the Quest came with as it is not the best quality and is quite faulty for anything save charging your device, it may work for a few installs but that is even if it lets your Quest be detected by SideQuest to begin with and even then it will quickly cease connecting properly to the point of it only being capable of charging your device.

If you have a phone USB cable that fits try that, If issues persist also try a different USB port such as a USB 2, USB 3 have issues some times with SideQuest, those ports will usually have a bit of blue when looking inside them so if you see blue within the USB slot you are trying to use try one that has a black inline. 

###### Be aware just because windows shows `Quest` DOES NOT mean it is a viable cord as some cords will only ever show what the device is and never let the user Open, modify or install things to the device. So be sure if your having issues to try a few different cables in a different port on your PC to see if your Quest registers to SideQuest then.

----
# 2 No Pop-up in headset to connect
----

Several things could cause that, Make sure your guardian is set up and active when looking, a standalone temporary one is fine, if still not showing, even if windows detects it, try a new cable as yours may not fully support data transfer or have been burnt out from prior use and reduced to (Charge only) mode, Also be sure SideQuest is opened and running.


----
# 3 Developer mode toggling
----

`Note that none of these steps are in about or with SideQuest and are done only within the mobile phone application for Oculus. Also, users usually need to toggle Developer mode after any Oculus OS update as it usually is auto disabled due to the update`

Open the official Oculus application on a Bluetooth capable phone or tablet and log into your Oculus account, go to `Settings` within the app and click your headset to connect, make sure the power is on when doing so, then click advanced settings and go to `Developer mode` to disable then re-enable it before hard rebooting your device, this is done by holding down the headsets power button for 15 seconds, then rebooting as normal.

###### If you turn Developer mode off in your Phone application and you suddenly your headset connects to SideQuest it is an error with the application thinking on is off and off is on, the following should fix it.

Open your Oculus Application on the device you set your Quest up with and head to settings while connected to your Quest via Bluetooth, After doing so try to Toggle Developer mode (at the least 3 times) Then set it back to enabled and restart your Quest device before you try to connect once again to SideQuest

`If the issue persists toggle Developer mode to enabled again, then power off your Quest completely while still on the Developer mode page in your phone application and disable it while your system is off, then turn your Headset back on, Reconnect it to your phone and Re-enable Developer mode`

###### Doing so in the phone app tends to solve many issues, also some times there is a glitch causing something to go awry, such as sometimes making the headset connect to SideQuest only when Developer mode is off and disconnect when it is on, the issue generally occurs on initial set up, after trying the installation steps more than once, or Re-Installing/Updating SideQuest.

----
# 4 Power cycling your devices 
----

Sometimes the best thing to try is a proper device power cycle of all devices involved. To do this start by unplugging your headset and turning your PC off completely to make sure all processes including ADB.exe, as well as any other possibly  conflicting software have entirely shut down, make sure you do not `Reboot` and have turned the computer completely off then wait a few seconds. After rebooting the PC proceed to hard reboot your headset by holding the power button for at least 7 seconds and wait over 5 seconds before re-powering it to be sure both systems are clean started, then re-open SideQuest on your PC and once more to try connect again to see if the issue has resolved.

----
# If you use or have Oculus LINK
-----

Link sometimes overrides ADB connections if open and in use whether running in the background quietly or not so
it is possible if you use LINK that your headset is upon being plugged into your PC automatically connecting to Oculus's software, Make sure that the Oculus software is closed completely in your computers Task Manager as well as your Task-bar
(lower right of Windows PC) and that your system has SideQuest open and is connecting to SideQuest properly.


----
# 6 Android Emulators and Routers
----

The use of Android Emulators can occasionally cause conflictions if running in the background and over riding the Quest drivers some where so if you have issues try to turn off completely and not running in task manager, if issues persist you can try uninstalling it to see if the issue resolves. 

For routers always connect your headset directly to the same router as your PC or phone to minimize issues try to avoid things like hotspots, router extenders, mesh networks and other smart connection systems and specialized settings. A Wi-Fi Extender of any kind can lead to a cascade of problems so if you do have any be sure to disable your VPN services of when using SideQuest to see if it helps, if it does it may be best to refrain from using it again with SideQuest they are all known to cause issues for SideQuest. With some VPN's such as NordVPN, users may get away with a simple to change a setting that masks your PC even when the VPN service is not actively running as some VPN services still control and mask your system in the background even when not actively open and running, Just locate the setting that disabled your VPN's ability to be masked/ Invisible to local LAN or through Wi-Fi.

###### For programs such as [BMBF](https://github.com/the-expanse/SideQuest/wiki/BMBF)(Beat Ons standalone replacement) you can install and manage songs in headset to avoid issues with that application specifically.

----
# 7 Power cycling your devices 
----

Next thing to try is unplugging your headset and turning your PC off completely to make sure all processes of ADB as well as any conflicting processes cease, make sure you do not `Reboot`, Turn the computer completely off and wait a few seconds, Also Hard reboot your headset by holding the power button for at least 15 seconds before restating it to be sure both systems are prepped, then turn your PC back on before re-opening SideQuest and trying once more to try connecting again.


# 8 Resetting your ADB connection 

To reset your connection just click the `Run ADB Commands` button top of SideQuest as seen here

![](https://cdn.discordapp.com/attachments/615234075778875453/622179541535817728/Screenshot_257.png)


Then click `Disconnect everything` hit `Run Command`, 
Go back again and hit `reset ADB`, then hit `Enable USB ADB` and you should connect.

----
# 9 For Wireless Connection 
----

Make sure to connect your headset once before you hit the connect button in the wireless connection popup.
When properly connected SideQuest should show a purple connection dot and then state two devices are connected, that is when you can disconnect your headset, Note that Every time you reboot SideQuest you will need to reconnect this way with a cable for initial connection.  Make sure your headset is on and connected to the same Wi-Fi network but otherwise you should now be capable of cordless installation, you can also while connected this way if away from home and logged into a SideQuest account install games from a phone or alternate PC from the SideQuestVR.com website.

----
# 10 Properly clean install from scratch
----
SideQuest uses some folders that are a bit hard to find or remove some times so to make sure everything is in order Install the [SideQuest Force Uninstaller](https://github.com/the-expanse/SideQuest/wiki/Force-Uninstaller-for-SideQuest) from that blue link text and install then run the program there, then reinstall the latest SideQuest again, this will remove any residual files, folders and settings that may be causing issues.

----
# 11 Driver Re-installation
----

If so far nothing else has worked the next thing to attempt would be a Driver re-installation, see how to do so at
[SideQuests Driver Re-installation tutorial](https://www.reddit.com/r/sidequest/comments/dsebyq/cant_connect_to_sidequest_tried_everything_ive/)

----
# 11 Force connect with CMD
----

### For both Mac and Windows

##### If you're on a Mac computer then you can also click the wrench icon in the top right and click “open ADB folder” - then drag these commands into a terminal window

##### For windows use the commands in `CMD` which can be found by using your `windows start tab` (bottom left windows button) and searching `CMD` then right click `CMD` and click run as Administrator

Type 
`cd %appdata%\SideQuest\platform-tools\`
Click enter Then
`adb devices`
Click enter

You should see:
List of devices attached
`Example1SOTGDHHSD93 device`


If you see 
`Example1SOTGDHHSD93 unauthorized`
put on your headset now you should see the message to allow usb debugging - click always allow. 

If you see  
`1SOTGDHHSD93  offline`
Then type 
`adb kill-server`
 and then use the `adb devices` command again.

If you see 
`Cannot connect to daemon` 
Then open up task manager and kill the adb.exe process by clicking it, then hitting end task for windows, else try the commands - taskkill /f /im adb.exe

----
## 12 Manual reinstallation of the necessary Platform Tools folder
----

Failing the above all the above (Windows only) Try reinstalling the ADB Platform Tools folder manually

These are only for windows, Also make sure to only do it if no other options available work and if you are still having issues with ADB try the below

Install the folder from 

[Platform Tools Zip folder](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)

Then proceed to unzip it,
`If you do not know how to check Google for how to unzip a folder for your version of windows`

Then in SideQuest head to settings
Then at the top of the page click `Open Main App` folder, remember the folder location and log out and back in to your PC's account, then navigate back to the folder manually using Windows file explorer (Not SideQuest) and look for the `Platform tools` Folder, delete the entire folder then move the extracted new platform tools folder you downloaded and extracted into its place, when finished reboot SideQuest and try once more to connect your headset.

----
# 13 Possible conflicting Software or VPNs
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609881862956908564/Screenshot_1164.png)

If you're using Bluestacks, NOX or an android emulator and are having connection issues you can try to close them and checking that one is not running in the background by checking your task manager.

----
#### [How to properly uninstall BlueStacks](https://github.com/the-expanse/SideQuest/wiki/BlueStacks-is-causing-issues,-how-do-i-remove-it)

----
# 14 Antivirus Systems
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609882817962442752/Screenshot_1165.png)

Antivirus applications such as AVG, Avast, BitDefender or similar programs can in rare cases cause issues so try to check if ADB.exe is running, if not see if it has been Quarantined/Vaulted by it and tell your antivirus to allow it through, if you do not know how to do this search Google for “how to allow a program through quarantine” for your specific Anti Virus software, for example if it is windows defender search how to for windows defender on your PC and allow SideQuest however the tutorial tells you to let programs through your system, if you have further issues try disabling your Anti-virus system for the duration of the SideQuest installation and see if doing so helps when launching SideQuest once more.

Note for Mac users you may need to allow SideQuest in your Privacy new settings.


----
# BMBF issues
----

###### We are not responsible for the BMBF application but here are a couple of things to try

### [Beatsaber Help Page](https://github.com/the-expanse/SideQuest/wiki/BMBF)

`If you still have issues you can ask around the official discord, if you already have done so you may check again as someone may have another idea to assist but do be aware that even if you are frustrated they are trying their best to assist out of the kindness of their hearts and with their free time so please do be kind, Thank you`