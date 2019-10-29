# FIRST BEFORE ANYTHING 
dis and Re:Enable Developer mode again right now from the Oculus application on your Phone/Tablet You set your Quest up with, Updating the Quest sometimes switches it off automatically but resetting it also helps the connection refresh.

----

If you are still having issues connecting to SideQuest after re-enabling developer mode,
it may be that the Oculus drivers have been uninstalled from your PC causing the issue due to the latest update, or the Driver may be corrupted, either way firstly go to this [Install drivers page](https://developer.oculus.com/downloads/package/oculus-go-adb-drivers/) on your PC and download the Drivers to your PC,
Though it may say it is for the GO The Oculus Go drivers are for the Quest.
To install the drivers extract the zip folder, then open the extracted folder and find the INF file to install as seen below.

![](https://sidequestvr.com/assets/images/right-click.png)


If that didn't solve the issue to fix it in windows just head to your PC's `device manager`

and in it if you see ADB interface like this

![](https://cdn.discordapp.com/attachments/615234122604085262/629749839718121546/12.png)


 Right click 
`ADB Interface`
and in the popup hit 
`update driver software`
in that pop-up click 
`browse my computer for driver software`

![](https://camo.githubusercontent.com/ed9362d3ded6cd7c70c3e22810141d7258ad222e/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3538313531393534393032373834343130362f3632393037353838323335383630333830362f53637265656e73686f745f3431302e706e67)

then at the bottom click 

`pick from a list of device drivers on my computer` 

![](https://cdn.discordapp.com/attachments/615234122604085262/629737481708896269/11.png)
then you should see 

`oculus device`

from there you should be able to find find the 

`oculus composite adb interface` 

option and install it 
![](https://cdn.discordapp.com/attachments/625267367513030656/638791603011715083/unknown.png)

if it dose not appear try to un-check "show compatible drivers" and look for it then
after that restart your PC and the issue should be resolved.

If you see this popup at any point just click yes
![](https://cdn.discordapp.com/attachments/541467913857662995/638831232360120391/unknown.png)


Last resort failing this sadly is a Factory reset, that helps many users get back online.