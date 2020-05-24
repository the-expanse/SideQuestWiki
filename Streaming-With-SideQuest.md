## You Can Stream Wireless on Mac Linux and Windows

![](https://cdn.discordapp.com/attachments/615234075778875453/704465986870575144/Screenshot_1606.png)

`Note Java is Required for some users of windows if not already installed you should get a prompt of such when attempting to run it of sorts, if so try installing the latest Java version for your OS depending on the OS version number associated with your PC 7/8/8.1/10`

You can do this by enabling Wi-Fi mode in the top right with the wireless button, make sure to be connected by cable when enabling this feature and wait until the connection dot is purple before unplugging then launch the streamer and you should see it pop up with your screen live, you can also install apps and manage in headset recorded material this way.

### Cable Needed To Enable, 
Though Wifi Mode Can Make Streaming Wireless After initial connection unfortunately yes a cable will be required even with wireless mode as you will need a cable to first initialize any type of connection to begin with, as well as every subsequent time you either reboot of your headset, or the PC as IPs can change and as a safety measure for users against hacking, it records and saves the IP of your device (which can change over restarts) if SideQuest is closed and reopened but upon a reboot of either device it will loose that connection so you will need to re-engage it with the cable once again.

### Make sure you unplug

After enabling Wireless mode it will think there are two devices connected at once as it accesses your Quest from both a Cable and the Wi-Fi, so be sure you unplug your cable and it has a green dot top right before running the Streamer


### There is no in built audio

There will be no game sound streaming and this feature is highly unlikely at all let alone any time soon so you will need an alternative solution none of which do not require some sort of hardware.

### Alternative Audio Solutions
`Note that all solutions require purchasing external software or hardware

You can use a Bluetooth transmitter plugged into your headset and a Bluetooth receiver hooked to your PC which shouldn't have notable lag at all with a good quality one (Always check the reviews if looking for good ones), Else you can use a proper physical AUX audio cable from your headsets headphone jack to your PC to allow transmission of in game sounds along side the Video or paying for AirReceiver which is well worth it if you plan to stream regularly and does both Audio and Video with minimal lag in great quality and requires little setup and can be used autonomously from SideQuest.


## **AirReciever Video tutorial**

[![Wireless Casting](https://cdn.discordapp.com/attachments/615234075778875453/714046991625224272/Screenshot_1678.png)](https://www.youtube.com/watch?v=s_0t593Ql1w)

### Cropping
The SideQuest streamer has it set to auto crop the original video usually sent to SCRCPY due to it being unsuitable for streaming to begin with, but you can change the crop to your liking in the settings and mess about with it.


# (Windows Only) If you are having issues running the Streaming feature in SideQuest here are a few things to try.

#### Double check ADB is coming from SideQuest

Run Windows Task Manager and locate ADB.exe, then right click it, if it does not open to a folder having to do with SideQuest unplug your headset stop ADB.exe and remove the conflicting ADB.exe from whatever folder opened before restarting SideQuest and trying again.

#### Make sure your headset screen is enabled

Check that your headset is not in sleep mode and that the screen is on and showing video, the streamer will show everything the headset sees so be aware is shows your room if you leave your guardian boundary as well.

#### Check for any alternate ADB versions.

Make sure to search your PC using auto search and whatever you can to check for any other versions of ADB.exe and remove them in case of interference before re launching SideQuest

#### Uninstall any old non SideQuest related versions of ScrCpy you may have installed before installing SideQuest

Make sure if you have installed ScrCpy before that you properly remove all related folders and files not in SideQuests folders, leaving any such files may lead to conflictions.

#### Check your AV

Antivirus systems such as Avast, BitDefender and Windows Defender have always has issues with SideQuest so be sure to try disabling them and see if it works then, you can also check your AV's system Quarantine, if you don't know how
[Click Here](https://www.google.com/search?rlz=1C1CHBD_enUS862US862&sxsrf=ACYBGNTOcP_sjV4YJm4NFJWMTR-ycYTJvQ%3A1576998921936&ei=CRj_XZfpOPqy0PEPteiuuAY&q=YOUR+AV+HERE+checking+quarantine+for+my+antivirus+system&oq=YOUR+AV+HERE+checking+quarantine+for+my+antivirus+system&gs_l=psy-ab.3...6171.33987..35807...1.2..0.242.3166.36j1j1......0....1..gws-wiz.......0i71j33i10.WnBt3GAw-08&ved=0ahUKEwjXkbbk2sjmAhV6GTQIHTW0C2cQ4dUDCAs&uact=5) ,

### Uninstalling the ScrCpy folder

Next you can try deleting the ScrCpy folder by going to the settings tab in SideQuest under the wrench icon and clicking `Open main app folder` then locating the ScrCpy folder, close SideQuest completely prior to deleting it and then after removal restart SideQuest and see if streaming functions properly then.

#### Environment Variables

If you had a previous streamer of some kind and it had a custom environment variable set it may be redirecting either ADB or ScrCpy. Removing any environment variables for ScrCpy should stop any redirect issues to unrelated or missing folders. After doing that close SideQuest it should fix it's self so you can utilize the streaming feature once more.

To do this type `env` into your start bar bottom left in windows and you should see `Edit the system environment variables` in system properties, click it open and then proceed to check any entries that contain SCRCPY and delete then.


### Try reinstalling 

If issues persist you can attempt a clean installation of SideQuest to see if it helps by using our force uninstaller at the [SideQuest force uninstaller](https://github.com/the-expanse/SideQuest/wiki/Force-Uninstaller-for-SideQuest#sidequest-clean-force-uninstaller) page and reinstall with windows defender or what ever antivirus system you have disabled temporarily 