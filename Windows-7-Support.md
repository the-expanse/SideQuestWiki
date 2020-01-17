## Windows 7 is not officially supported
The below information is provided as is and without warranty. SideQuest does not support windows 7 but we have had reports that it can work. The most difficult part is usually the driver installation which we go into more detail on below. 


## This guide is for Windows 7 manual installation

Windows 7 systems have a good chance to install SideQuest but you will need to install the drivers needed for SideQuest manually.
First you must go through everything in the [Setup Instructions](https://sidequestvr.com/#/setup-howto) up to step 3, install the folder and extract it as stated in that guide and then install the drives manually as dictated below.

### Simple Manual Drivers installing for Windows 7

###### Your Headset must be turned on prior to you connecting it to your Computer and be sure to use a data capable cord/cable, not the cable the Quest was provided with, some cables laying around the house may not be data capable for ADB either so be aware.

Open `Windows Explorer` and navigate to the list panel on the left of the window, Right click on either `Computer` or `This PC` and select Manage from the list of actions.

Locate `Other device` and open it to see `ADB Interface` of which should appear in the drop down, right-click `ADB Interface` and select Update Driver Software. 

![](https://cdn.discordapp.com/attachments/615234075778875453/659967062306848768/unknown.png)

Make sure you have the drivers you obtained from the official [Sidequest Installation how to](https://github.com/the-expanse/SideQuest/wiki/SideQuest-Setup-&-How-To-install#step-3-install-drivers-windows-users-only)

and that they are properly extracted, be that with WinRAR or 7Zip (Free online via google) or another built in extractor program.

Navigate the popups until you see `Have Disk` and click `Have Disk` and locate the extracted folder with the driver in it,
install `ADB Composite` for ADB interface, after that let it install and click ok, then locate the XRSP driver in your device manager and do the same, but after selecting the driver file in the folder, choose The one that mentions`Bootloader`



![](https://cdn.discordapp.com/attachments/615234075778875453/659968807250690111/unknown.png)

Locate the entire unzipped folder with the Oculus drivers in it that you have installed and extracted

![](https://cdn.discordapp.com/attachments/615234075778875453/659970285679804419/unknown.png)

(most likely in downloads) and select the folder, then click Next and it should install the driver, then just restart SideQuest and see if it connects now.

Beyond that you can see if this page helps

[Install OEM USB drivers](https://developer.android.com/studio/run/oem-usb)

If all else fails you can try to see if upgrading your system to windows 8 or 10 is an option to you,
All we can suggest if you can not get SideQuest running on Windows 7 with this page and information is to upgrade as even Microsoft themselves no longer support Windows 7.

If you do upgrade you should be able to start using all it's functions as well as SideQuest itself right away after installing the drivers from [These Steps](https://sidequestvr.com/#/setup-howto) , extract themm right click Win_Usb and clicking install but for that easy way to install Windows 8 or 10 is required.