## Windows 7 is not officially supported and Windows 8-8.1 have a few issues 
The below information is provided as is and without warranty as SideQuest does not have much ability to directly support Windows 7 or either of the Windows 8 operating systems but there are a few things you can try. The most issue is usually the driver installation of which sadly Oculus themselves have since dropped support for so the below may do little but you can certainly still attempt it.


## First thing to try

You can attempt install of the official Oculus software from https://www.oculus.com/setup/ to help install the needed drivers and start connecting to your Quest properly, after installing and running just close the software and launch SideQuest from your computer to see if your set up properly

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