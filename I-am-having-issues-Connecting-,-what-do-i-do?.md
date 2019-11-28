## Having connection issues? 

You want the dot in the top left inside SideQuest to be green and state it is connected, or yellow with instructions.


#### First things to try


Make sure you have installed the very latest SideQuest from [SideQuestVR.com](https://sidequestvr.com/#/download) properly before proceeding.
Also double check the main setup steps for installing SideQuest to make sure you have done every one of the 5 mandatory steps.


## [Setup Steps](https://sidequestvr.com/#/setup-howto) 
----

### BMBF issues

###### We are not responsible for the BMBF application but here are a couple things to try
1. Try to re launch BMBF while SideQuest is NOT open or running, failing that close BMBF and Open SideQuest, then top right click the (RUN ADB commands) button and then in order click `Disconnect everything` then `Reset ADB`before closing SideQuest and re attempting

If not BMBF related see below


# Common issues and possible solutions


----
Check Oculus LINK
-----

Make sure if you use LINK that your headset is not upon being plugged into your PC automatically connecting to Oculus's software, make sure that the Oculus software is closed completely in your computers Task Manager, or in your Taskbar (lower right of windows PC) and that your system has SideQuest open and is connecting to SideQuest properly

----
No Pop-up in headset to connect
----

Several things could cause that, Make sure your guardian is set up and active when looking, a standalone temporary one is fine, if still not showing, even if windows detects it, try a new cable as yours may not fully support data transfer or have been burnt out from prior use and reduced to (Charge only) mode, Also be sure SideQuest is opened and running.


----
Re:Toggle and Reset Dev mode
----

Note you should toggle Developer mode after any Oculus OS update as it usually is auto disabled due to the update.

###### If you turn Dev mode off and you suddenly connect it is an error with the application thinking on is off and off is on, the following should fix it.

Head back in your Oculus Application on the device you set your Quest up with and head to settings while connected to your Quest via Bluetooth, after doing so try to Toggle Dev mode at least 3 times then back to enabled and try to connect once again, if the issue persists toggle Dev mode to enabled again, then power off your Quest completely while still on the Dev mode page in your phone application and disable it while your system is off, then turn your Headset back on, Reconnect it to your phone and Re-enable Dev mode,

###### Doing so in the phone app tends to solve many issues, also some times there is a glitch causing something to go awry, such as sometimes making the headset connect to SideQuest only when Dev mode is off  and disconnect when it is on, the issue generally occurs on initial set up, after trying the install steps more then once, or Re-Installing/Updating SideQuest.

----
A different cord
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609880483286876218/Screenshot_1163.png)

Make sure to abstain from using the cord the Quest came with as it is not the best quality and is quite faulty for anything save charging your device, it may work for a few installs but will very quickly never connect again, If you have a phone USB cable that fits use that, Also try a different USB port, be aware just because windows shows `Quest` DOES NOT mean it is a viable cord as some cords will only ever show what the device is and never let the user Open, modify or install things to the device. So be sure if your having issues to try a few diffrent cables in a diffrent port on your PC to see if your Quest registers to SideQuest then.

----
NO VPN
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609881862956908564/Screenshot_1164.png)

if your using Bluestacks, NOX or a Wifi Extenders of any kind can lead to problems as well, Also be sure to disable ANY VPN services of any kind when using SideQuest, best to refrain from them as they are all known to cause issues for SideQuest.

For some VPN's such as NordVPN users, you may need to change a setting that masks your PC even when the VPN service is not actively running as some VPN services still control and mask your system in the background even when not actively open and running, Just locate the setting that disabled your VPN's ability to be masked/ Invisible to local LAN or through Wifi

----
## [How to properly uninstall BlueStacks](https://github.com/the-expanse/SideQuest/wiki/BlueStacks-is-causing-issues,-how-do-i-remove-it)

----
Antivirus systems
----

![](https://cdn.discordapp.com/attachments/608376262347587595/609882817962442752/Screenshot_1165.png)

Antivirus applications such as AVG, Avast, BitDefender or similar programs can cause issues so try to check if ADB.exe is running, if not see it it has been Quarantined/Vaulted by it and tell your antivirus to allow it through, if you do not know how to do this search google for "how to allow a program through quarantine" for your spastic Anti Virus, if it is windows defender, search it for windows defender on your PC and allow it there.

----
Android Emulators
----

The use of Android Emulators cause issues if it is being detected first, so make sure it is turned off completely and not running in task manager, as well as have it not set to "start on boot" in your Computer settings, or just uninstall it to remove the issue.

----
Your Router
----

Always try to connect directly to the same router as your PC or phone to minimize issues, avoid things like hotspots, router extenders, mesh networks, smart,connection systems and other specialized settings,
For BMBF (Beat Ons standalone replacment) just install and manage songs in headset to avoid issues with that application specifically 

----
Your Computer
----
Next thing to try is unplugging your headset and turning your PC off completely to make sure all processes of ADB as well as any conflicting processes cease, make sure you do not `Reboot`, Turn the computer completely off and wait a few seconds, Also Hard reboot your headset by holding the power button for at least 15 seconds before restaring it to be sure both systems are prepped, then turn your PC back on before re-opening SideQuest and trying once more to try connecting again.


### Resetting your connection and/or connecting to wi-fi

To reset your connection just click the `Run ADB Commands` button top of SideQuest as seen here

![](https://cdn.discordapp.com/attachments/615234075778875453/622179541535817728/Screenshot_257.png)


then click `Disconnect everything` hit `Run Command, 
Go back again and and hit `reset ADB`, then hit `Enable USB ADB` and you should connect

----
### For wireless connection 

Make sure to connect your headset once before you hit `Run ADB Commands, and then you can hit `Enable Wifi ADB`
after that just hit `Connect to Wifi ADB" and it should then state two devices are connected, disconnect your headset and now you are in wireless, mode, every time you reboot SideQuest you can click `Connect to Wifi ADB` and it will connect so long as your headset is on and connected to the same Wifi network, sometimes you will need to reconnect to update the Quest IP by hitting `Enable Wifi ADB` again but otherwise you are now capable of cordless installation.

----
### Nothing so far has worked?

If so far nothing else has worked the next thing to attempt would be a Driver re-installation, see how to do so at
[SideQuests Driver Re-installation tutorial](https://www.reddit.com/r/sidequest/comments/dsebyq/cant_connect_to_sidequest_tried_everything_ive/)

Failing the above  all of the above (Windows only) Try Installing the ADB folder manually
----

This is only for windows, Also make sure to only do it if no other options available work and if you are still having issues with ADB try the below

----
Install the below Folder
----
[Entire ADB folder](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)

then proceed to unzip it,
if you do not know how to, check google for how to unzip a folder for your version of windows,
then in SideQuest head to settings
Then at the top of the page click `Open Main App` folder and proceed to look for the (Platform tools) Folder
Open it, make sure to close SideQuest, then delete everything in that folder before you then copy and paste all the files and folders from the installed unzipped folder into it and click replace all, when finished  reboot SideQuest and try once more.





If you still have issues you can ask around the official discord, if you already have done so you may check again as some one may have another idea to assist but do be aware that even if you are frustrated they are trying their best to assist out of the kindness of their hearts and with their free time so please do be kind, Thank you