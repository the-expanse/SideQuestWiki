#### Below is the full guide to properly manually installing your Quest drivers on Windows 10. For Windows 7/8 or 8.1 the instructions are very similar, though there might be slight differences this guide should be able to get you to the proper pages and steps. 

Some drivers are not automatically installed and the device simply will not connect, just because your headset connects as a MTP device or media device to Windows or popups up in the headset asking you to allow, it can be asking to allow access to the files not the ADB allow popup.
If there is no checkbox for "Always Allow from this PC" the first time you are not properly connecting


## Prerequisites

-  Make sure that your Oculus Quest is connected to your PC via a proper data capable USB cord/cable, d not use the one provided with the device by Oculus.

-  That your Quest is the only android device connected to your PC and you have followed all the steps [HERE](https://github.com/the-expanse/SideQuest/wiki/SideQuest-Setup-&-How-To-install) to setup developer mode and get everything with SideQuest prepared 

-  And to Double check that developer mode is enabled in the Oculus App on your phone by toggling it off and on again for restart.



### Step 1
Search for `Device Manager` in the start menu and click it to open it.

![](https://cdn.discordapp.com/attachments/541467913857662995/641732058309459978/Screenshot_781.png)



### Step 2
Look for a device called `ADB Interface` inside a section called "Other Devices". Right click it and select `Update Driver`

![](https://cdn.discordapp.com/attachments/541467913857662995/641728713603416075/Screenshot_780.png)

If you don't see `ADB Interface` in the list try to connect your headset back up using a new USB cable/cord.



### Step 3
When the popup below appears select `Browse my computer`

![](https://cdn.discordapp.com/attachments/541467913857662995/641735135414190090/Screenshot_779.png)

Then click `Let me pick from a list`

![](https://cdn.discordapp.com/attachments/541467913857662995/641734956950880260/Screenshot_783.png)

### Step 4
On the on the next screen Find `Oculus Device`

![](https://cdn.discordapp.com/attachments/541467913857662995/641738916373856277/Screenshot_784.png)

And select within as shown below locate and select `Oculus Composite ADB Interface` then click next

![](https://cdn.discordapp.com/attachments/541467913857662995/641736416199442434/1_2.png)

Then click next as shown.

### Step 5


If you don't see the `Oculus Device` then follow Step 3 [HERE](https://github.com/the-expanse/SideQuest/wiki/SideQuest-Setup-&-How-To-install#step-3-install-drivers-windows-users-only).


If you see a warning about installing the driver just click `Yes`if it appears.

![](https://cdn.discordapp.com/attachments/541467913857662995/641731673871876118/Screenshot_782.png)

Repeat same process for XRSP Interface but at the end choose "Oculus Bootloader Interface" for XRSP Interface and you should be set.

After that just restart everything your PC and your Headset and then open SideQuest again and you should be functioning, if not see our [Official connection issue solution list](https://github.com/the-expanse/SideQuest/wiki/I-am-having-issues-Connecting-,-what-do-i-do%3F).