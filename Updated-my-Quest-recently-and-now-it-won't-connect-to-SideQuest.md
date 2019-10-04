Re Enable Developer mode from the Oculus application on your Phone/Tablet as Updating the Quest some times switches it off automatically

If you are still having issues connecting to SideQuest, and re-enabling developer mode did not fix the issue, 
it may be that the Oculus drivers have been uninstalled from your PC causing the issue due to the latest update, so to check and fix that in windows just head to your device manager

if in device manager you see something like this

![](https://cdn.discordapp.com/attachments/615234122604085262/629749839718121546/12.png)


with unknown drivers, right click 
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

option and install it after that restart your PC and the issue should be resolved.

Last resort failing this sadly is a Factory reset, that helps many users get back online.