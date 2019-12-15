## This guide also is for general Windows 7-10 manual installation

Windows 7 has been known to cause issues when installing SideQuest and sometimes will never properly install certain important needed assets, you might be able to get it running but it is unlikely, see if you can install the drivers needed for SideQuest by attempting to follow the [Setup Instructions](https://sidequestvr.com/#/setup-howto) and see if it works just be sure to install the drives manually.

### Simple Manual Drivers installing for Windows 7
Go to your device manager and locate then right click`ADB Interface` within the list of devices then right click it and select `update driver`, 

![](https://preview.redd.it/rlqn5xs4h1x31.png?width=974&format=png&auto=webp&s=9c654df16beb9a9ccb7eeae0917a767a87fe8517)

In the popup click browse and locate the extracted driver you obtained from the official [Sidequest Installation how to](https://github.com/the-expanse/SideQuest/wiki/SideQuest-Setup-&-How-To-install#step-3-install-drivers-windows-users-only) 


Also do make sure you actually extract it, after that it should load in the drivers.


## Expanded Manual Drivers installing for Windows 7

Make sure your Headset is turned on prior to you connecting your headset to your Computer and that you are using a data capable cord/cable, then open your `Windows Explorer` and navigate to the list panel on the left of the popup, Right click on either `Computer` or `This PC` and select Manage from the pop-up. then select `Devices` in the left pane, Then locate `Other device` and open it to see `ADB Interface` of which should appear in the drop down, right-click `ADB Interface` and select Update Driver Software. 

![](https://preview.redd.it/rlqn5xs4h1x31.png?width=974&format=png&auto=webp&s=9c654df16beb9a9ccb7eeae0917a767a87fe8517)

After that select `Browse My Computer for driver software` 

![](https://preview.redd.it/7tx1ubgbh1x31.png?width=614&format=png&auto=webp&s=6c0151a2facd3c818eaa7aefaed17e8c7dce15e7)


Then click Next, you will see another windows pop up

![](https://preview.redd.it/rpcg5jnhh1x31.png?width=613&format=png&auto=webp&s=35302cf1e1f42c3b6a4c3ba623601ea351f5e80e

Click `Let me pick from a list of available drivers` to make a pop-up window appear and in it locate the entire unzipped folder with the Oculus drivers in it that you have installed and extracted, (most likely in downloads) and select the folder, then click Next and it should install the driver, then just restart SideQuest and see if it connects now.

Beyond that you can see if this page helps

[Install OEM USB drivers](https://developer.android.com/studio/run/oem-usb)

If all else fails you can try to see if upgrading your system to windows 8 or 10 is an option to you but that is all we can suggest if you can not get SideQuest running on Windows 7 as even Microsoft themselves no longer support it, 
if you do upgrade you should be able to start using all it's functions as well as SideQuest itself right away after installing the drivers from [These Steps](https://sidequestvr.com/#/setup-howto) after that all should work perfectly with no issues at all