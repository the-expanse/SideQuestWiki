
# Having issues connecting or installing?

If everything at the [Service Desk connection page](https://sidequestvr.atlassian.net/servicedesk/customer/portal/1/article/180092929?src=1414971443) fails to help try the following solutions.

### Be sure to check below for a list of all supported devices SideQuest can be installed to as well as a sub-list of known non supported ones.

### [List of Supported Devices](https://github.com/the-expanse/SideQuest/wiki/Supported-Devices)
----
`Note SideQuest is based on and for the Oculus Quest and that Non Standalone headsets that do not use Android or have their own built in storage are not able to work with or utilize SideQuest, be sure when plugging in your Quest that SideQuest is open and running on your computer when trying to connect`
# Installation location
----
SideQuest can NOT be installed to a external or secondary drive it must be installed onto the main drive of the computer (The default being C)
As well as the Oculus drivers themselves else the program will not function properly if at all when run.

## If only some games are not installing properly
----
If you are unable to install only some of the time or specific larger games like Pavlov or Contractor$ are not installing properly try to enable wireless mode under the Wifi icon top right, after enabled wait for a tiny white arrow to appear at the very top left beside the connection dot  before disconnecting your headset and if you see a green dot appear then attempt installation of the application once more , That should resolve most issues and be sure to give installs of games like that a good 5 minutes more after they are done installing before launching or restarting your device to let the large installations finish on device being registered to prevent corruption, If this does not help you try the solutions below.

Make sure you have installed the proper and most recent version of SideQuest from [SideQuestVR.com](https://sidequestvr.com/#/download) correctly before proceeding.

If having issues still double check you completed all 5 of the required setup steps for installing SideQuest [Mandatory setup steps](https://github.com/the-expanse/SideQuest/wiki/SideQuest-Setup-&-How-To-install#step-1-install-sidequest-to-your-computer).

# [Setup Steps](https://sidequestvr.com/#/setup-howto) 

----

# Our List of Alternative Connection Solutions


----
## A new PC user account
----

One super quick fix for most issues is to try making a new "administrator" user account for your PC and install SideQuest to the clean desktop of that user, if it connects straight away you more then likely have conflicting software on your main computer user account or a issue with your USB cable, If unsure how to create a new user on your own PC and operating system best go [HERE](https://www.google.com/search?sxsrf=ALeKk019E5PfkP2rN7OvOdtrz1UA1uBhBw%3A1589591099829&ei=Ozy_XoCXMr7M0PEPjMyn0Ao&q=how+do+i+make+a+new+user+account+for+%28Do+you+use+windows%2C+mac+or+linux%29&oq=how+do+i+make+a+new+user+account+for+%28Do+you+use+windows%2C+mac+or+linux%29&gs_lcp=CgZwc3ktYWIQAzoECAAQRzoECCEQClD_QlifggFgopEBaANwAXgAgAFuiAGAC5IBBDE0LjKYAQCgAQGqAQdnd3Mtd2l6&sclient=psy-ab&ved=0ahUKEwjAoN-mmLfpAhU-JjQIHQzmCaoQ4dUDCAw&uact=5)

## Reinstall SideQuest
----
First thing to try is the simplest, try uninstalling then Re:installing SideQuest completely from
[SideQuestVR.com/Download](https://sidequestvr.com/setup-howto) for your OS and run it again to see if it connects after 10 seconds or so, this solution is for any issue and well worth trying, sometimes a reinstall is all it takes to solve a bug or a glitch.


----
## No Pop-up in headset to connect
----

Several things could cause this issue, One solution could simply be to make sure a guardian is set up and active when looking, a temporary one is fine, else make sure to check you installed the Drivers properly if on windows from Step 3 of https://sidequestvr.com/setup-howto .


----
## Power cycling your devices 
----

Next try unplugging your headset from the PC and turning your PC off completely, Make sure you don't `Reboot`, Turn the PC completely off and wait a few seconds then hard reboot your headset by holding the power button for at least 15 seconds before restating it to be sure both systems are restarted clean, After that turn your PC and headset back on before re-opening SideQuest and try connecting again.

----
## If you use or have Oculus LINK
-----

Link sometimes overrides ADB connections if open and in use whether running in the background quietly or not so
it is possible if you use LINK that your headset is upon being plugged into your PC automatically connecting to Oculus's software, Make sure that the Oculus software is closed completely in your computers Task Manager as well as your Task-bar
(lower right of Windows PC) and that your system has SideQuest open and is connecting to SideQuest properly.

----
## Conflicting ADB version (Windows only)
----

If you have used android devices before it is possible you have already installed a program called ADB.exe, this program is core to how SideQuest connects to the Quest and if there is another version installed on a PC it can cause cascading effects resulting in many connection issues, from inconsistent installations, to not connecting at all. To try to fix such issues when you start your PC go to your Windows file explorer (not Internet Explorer), on the left side in the file explorer locate "This PC" and open it so you can see your main computer drive, after you open "this PC" click the `Search` bar top right of the popup, then in the search box type in `ADB.exe` and let it load for a bit, If more than one file or folder mentioning ADB shows up select each one, right click them all and click delete, If one is in use and is unable to be uninstalled open your windows "Task manager" and locate ADB.exe and select it then select "End process" and try again, it should be able to be deleted then. If not remember what folder the file was in, restart your PC and immediately find and remove it before starting any program it may be associated with. After you have removed any conflicting ADB.exe programs restart SideQuest and it will reinstall ADB.exe automatically and should function normally unless there is another cause of the issue.

----
## Android Emulators and Routers
----

The use of Android Emulators can occasionally cause program conflictions if running in the background, Over riding the Quest drivers. To test for and fix such issues open windows task manager, then locate any known emulators installed, if running stop them and restart SideQuest. if issues persist you can try uninstalling it to see if the issue resolves. 

For Routers, always connect your headset directly to the same router as your PC or phone to minimize issues try to avoid things like hotspots, router extenders, mesh networks and other smart connection systems and specialized settings. A Wi-Fi Extender of any kind can lead to a cascade of problems so if you do have any be sure to disable your VPN services of when using SideQuest to see if it helps, if it does it may be best to refrain from using it again with SideQuest they are all known to cause issues for SideQuest. With some VPN's such as NordVPN, users may get away with a simple to change a setting that masks your PC even when the VPN service is not actively running as some VPN services still control and mask your system in the background even when not actively open and running, Just locate the setting that disabled your VPN's ability to be masked/ Invisible to local LAN or through Wi-Fi.

###### For programs such as [BMBF](https://github.com/the-expanse/SideQuest/wiki/BMBF)(Beat Ons standalone replacement) you can install and manage songs in headset to avoid issues with that application specifically.

----

## Resetting your ADB connection 
----

To reset your connection just click the `Run ADB Commands` button top of SideQuest as seen here

![](https://cdn.discordapp.com/attachments/615234075778875453/704453481746137088/Screenshot_1596.png)


Then click `Disconnect everything` hit `Run Command`, 
Go back again and hit `reset ADB`, then hit `Enable USB ADB` and you should connect.

----
##  For Wireless Connection 
----

Make sure to connect your headset once before you hit the connect button in the wireless connection popup.
When properly connected SideQuest should show a purple connection dot and then state two devices are connected, that is when you can disconnect your headset, Note that Every time you reboot SideQuest you will need to reconnect this way with a cable for initial connection.  Make sure your headset is on and connected to the same Wi-Fi network but otherwise you should now be capable of cordless installation, you can also while connected this way if away from home and logged into a SideQuest account install games from a phone or alternate PC from the SideQuestVR.com website.

----
## Properly clean install from scratch
----
SideQuest uses some folders that are a bit hard to find or remove some times so to make sure everything is in order Install the [SideQuest Force Uninstaller](https://github.com/the-expanse/SideQuest/wiki/Force-Uninstaller-for-SideQuest) from that blue link text and install then run the program there, then reinstall the latest SideQuest again, this will remove any residual files, folders and settings that may be causing issues.

----
## Driver Re-installation
----

If so far nothing else has worked the next thing to attempt would be a Driver re-installation, see how to do so at
[SideQuests Driver Re-installation tutorial](https://www.reddit.com/r/sidequest/comments/dsebyq/cant_connect_to_sidequest_tried_everything_ive/)

----
## Force connect with CMD/Terminal 
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
## Manual re-installation of the necessary Platform Tools folder
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
## Possible conflicting Software or VPNs
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609881862956908564/Screenshot_1164.png)

If you're using Bluestacks, NOX or an android emulator and are having connection issues you can try to close them and checking that one is not running in the background by checking your task manager.

----
#### [How to properly uninstall BlueStacks](https://github.com/the-expanse/SideQuest/wiki/BlueStacks-is-causing-issues,-how-do-i-remove-it)

----
## Antivirus Systems issues
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609882817962442752/Screenshot_1165.png)

Antivirus applications such as AVG, Avast, BitDefender or similar programs can in rare cases cause issues so try to check if ADB.exe is running, if not see if it has been Quarantined/Vaulted by it and tell your antivirus to allow it through, if you do not know how to do this search Google for “how to allow a program through quarantine” for your specific Anti Virus software, for example if it is windows defender search how to for windows defender on your PC and allow SideQuest however the tutorial tells you to let programs through your system, if you have further issues try disabling your Anti-virus system for the duration of the SideQuest installation and see if doing so helps when launching SideQuest once more.

Note for Mac users you may need to allow SideQuest in your Privacy new settings.


----
## BMBF issues
----

###### We are not responsible for the BMBF application but here are a couple of things to try

### [Beatsaber Help Page](https://github.com/the-expanse/SideQuest/wiki/BMBF)

----
Please Be Kind
----

`If you still have issues you can ask around the official discord, if you already have done so you may check again as someone may have another idea to assist but do be aware that even if you are frustrated, They are trying their best to assist out of the kindness of their hearts and with their own limited free time so please do be kind, Thank you`