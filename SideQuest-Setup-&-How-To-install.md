### SideQuest is for PC only, not Mobile Phones or Headsets

What Is SideQuest and What Does It Allow

`SideQuest is a side-loading application that does not support piracy. SideQuest requires an external device (A PC) in order to side-load games from and applications from the install-able launcher from` [SideQuestVR.com](https://sidequestvr.com/setup-howto), `Installing SideQuest the application to your actual Quest device to download apps and games all directly within a headset like the official Oculus store without a PC ever again is not something we can do, Also note that the "SideQuest" application within SideQuestVR.com's own App Store is only a 2D game launcher for non nativity supported phone applications and apps installed with SideQuest from on your PC, SideQuest Legends will also not be capable of doing so due to code infringement concerns and security issues.`

## For any connection or installation issues you can check our [Connection Issues and Solutions](https://github.com/the-expanse/SideQuest/wiki/I-am-having-issues-Connecting-,-what-do-i-do%3F) page for known issues and solutions.

To see if the OS of the PC, As well as the headset you are using are both actually supported check out our.
## [Supported Devices Page](https://github.com/the-expanse/SideQuest/wiki/Supported-Devices)


## Before installation

Know that Unknown Sources will NOT appear until you successfully install an application or game from an external source, that is not the Oculus store. 

If you are on Version 15 or higher of the Quest OS, Unknown sources is in a new location
[Where is Unknown Sources in V15 of Oculus Quest](https://github.com/the-expanse/SideQuest/wiki/SideQuest-Setup-&-How-To-install#for-v15-of-oculus-quest-unknown-sources-will-be-located-as-shown-below-for-users)

Make sure before anything to `use a phone USB cable that can transfer data` instead of the cable that comes with your Quest as the cable that comes with the device generally is cheap and not suited for data transfer, Also note that making a SideQuest account helps in many ways such as with updating your apps as easily as possible so be sure to look into making an account if interested in the wide growing array of QoL features we offer.
[SIGN UP HERE](https://sidequestvr.com/#/sign-up)

## Windows Video Installation Tutorial

[![Video Tutorial](https://cdn.discordapp.com/attachments/615234075778875453/672161163072634880/Screenshot_1254.png)](https://www.youtube.com/watch?v=reH55tb9w84)

## Mac Video Installation Tutorial

[![Video Tutorial](https://cdn.discordapp.com/attachments/615234075778875453/668592647018905600/Screenshot_1208.png)](https://www.youtube.com/watch?v=xKUvK2Pmv8o)

For the official SideQuest Website tutorial see

https://sidequestvr.com/#/setup-howto

Step 1: Install SideQuest To Your Computer
====================================================

Be sure to click your related OS out of the links shown below to download and install SideQuest before you continue with these steps, Windows users use the .EXE, Mac users use the DMG and so on, Windows 7 and 8.1 are not properly supported so if you have yet to do consider upgrading for free at https://www.bleepingcomputer.com/news/microsoft/you-can-still-upgrade-to-windows-10-for-free-heres-how/


[![SideQuest Installer](https://cdn.discordapp.com/attachments/615234075778875453/737756550453788802/Screenshot_1841.png)](https://sidequestvr.com/#/download)


 [Install SideQuest](https://sidequestvr.com/#/download)

Step 2: Create Organization
====================================================

To be able to sideload to the Headset at all you have to be a registered "developer" first, it is very important so be sure to go to [Create new organization](https://dashboard.oculus.com/organizations/create/) on your PC and log in so you can make a dummy organization name. You'll be asked to accept the developer agreement, do so and then your set to move on.

Step 3: IMPORTANT, Install Drivers (Windows users Only)
====================================================

(Windows 7/ 8 users see [here](https://github.com/the-expanse/SideQuest/wiki/I-Have-Windows-7,-can-i-use-SideQuest%3F) )

Make sure before anything further to use a proper cable, such as phone USB cable that can transfer data instead of the cable that comes with your Quest as the cable that comes with the device is not suited for data transfer.

To properly install the driver software for your device into windows. First Go to this [Install drivers page](https://developer.oculus.com/downloads/package/oculus-go-adb-drivers/) on your PC and download the folder containing the drivers to your PC, then locate the drivers ZIP folder and extract the zip folder as shown below.

`(Though it may say it is for an Oculus GO The Oculus Go drivers work for the Quest as well)`

Extract them with either the inbuilt windows extractor as seen below

![](https://cdn.discordapp.com/attachments/615234075778875453/714213057529774090/Screenshot_1661.png)

Or 7-Zip which you can install from https://www.7-zip.org/ (WinRar not suggested)

![](https://cdn.discordapp.com/attachments/608376262347587595/608756299177656320/extract_drivers.png)

After you exact it via the picture above or with Windows built in extract button go into the new un-extracted folder,

![](https://cdn.discordapp.com/attachments/608376262347587595/608755536984277002/Screenshot_1106.png)

and right click the android_winusb.inf file to click install.

![](https://cdn.discordapp.com/attachments/608376262347587595/608755617242546233/drivers.png)

Note that it may or may not have `.inf` at the end, both are the exact same file so do not worry about it being there or missing as that is normal.

Step 4: Reboot & Enable Developer Mode
====================================================
Now that you're a "developer" in Oculus's system, open the Oculus app on your smartphone or tablet. and follow the steps below from the Oculus application gotten for initial device setup, This process is not done in Headset, you must connect your headset over Bluetooth to your Phone or Tablet that you set the Quest up in. You may need to toggle it once or twice to get it enabled properly, failing that try enabling it turning your headset off completely for at least 12 seconds, then re-powering the device 
and moving to step 5.
![](https://cdn.discordapp.com/attachments/608376262347587595/609103817178611732/Screenshot_2019-08-07-13-23-35.png)
![](https://cdn.discordapp.com/attachments/608376262347587595/609103731979714597/Screenshot_2019-08-07-13-23-39.png)

![](https://cdn.discordapp.com/attachments/608376262347587595/608760168230027264/enable_Dev_mode.png)

Also make sure to Disable Unlock Pattern if it is enabled,

![](https://cdn.discordapp.com/attachments/608376262347587595/609104317001105411/disable_unlock_patt.png)

Make sure it asks if you want to "set unlock pattern" as that means it is off like it should be

Once you have enabled developer mode MAKE SURE TO REBOOT YOUR HEADSET to let your PC be able to see the device.

Step 5: Connect USB Cable and Allow USB Debugging
====================================================

Now it's time to connect the USB cable. make sure a guardian is set up around your headset so that once you are connected you will have to allow USB debugging `access inside your headset`. If you put your headset on at this point should see the below. 

![](https://cdn.discordapp.com/attachments/608376262347587595/608761133444235275/Screenshot_1113.png)


if it does not appear and you are on windows, be sure to set up a standalone guardian and that you have SideQuest opened


## For V15 of Oculus Quest Unknown sources will be located as shown below for users

![](https://cdn.discordapp.com/attachments/625267367513030656/696615350292185109/2.png)


OPTIONAL
----

Step 6: Install App Launcher
====================================================

Installing the launcher will just make finding Sideloaded apps easier on your headset, it is not an installer only a sorting and convenience app.
Make sure you are properly connected to SideQuest before proceeding, and install it from SideQuests PC launcher while properly connected
If not properly connected see here.
[I'm having connection issues what are some solutions](https://github.com/the-expanse/SideQuest/wiki/I-am-having-issues-Connecting-,-what-do-i-do%3F#resetting-your-connection-and-connecting-to-wifi)

The launcher will be found in headset after installed in you library under 'Unknown Sources' on the menu on the left.
Open it to find all the Apps that have been installed on your device.


Install 
[Quest App launcher](https://sidequestvr.com/#/app/199) 
and hit install latest, then go back to your browser to click confirm.

Be sure to go back to the browser and click confirm in your web browser, then you are set to go.

You can now install Apps to your headset and open them from the SideQuest launcher.
You can find it in the side-menu of the library under the Unknown Sources section called SideQuest - TV as well as SideQuest - Home. This will show you all the Apps on the device even hidden ones you would otherwise not see, to fast launch some Apps you can install the official OculusTV from the store and open it from your O-Bar with the (TV) button in headset and just scroll to the bottom, you will find most Apps there as well.

## To learn about BeatSaber and how to Install custom songs to it with Beat on just go [HERE](https://github.com/the-expanse/SideQuest/wiki/BMBF#bmbf-is-a-custom-song-installer-for-beatsaber)