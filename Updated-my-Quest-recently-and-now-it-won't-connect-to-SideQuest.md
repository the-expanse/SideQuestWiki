Re Enable Developer mode from the Oculus application on your Phone/Tablet as Updating the Quest some times switches it off automatically

If you are still having issues connecting to SideQuest, and re-enabling developer mode did not fix the issue, 
it may be that the Oculus drivers have been uninstalled from your PC causing the issue due to the latest update, 

in windows just head to your device manager and search for 
`adb interface` 
when found then right-clicking 
`adb interface` and in the popup hit `update driver software`
in that pop-up click 
`browse my computer for driver software`
 and at the bottom click 
`pick from a list of device drivers on my computer` 
then you should see 
`oculus device`
from there you should be able to find find the 
`oculus composite adb interface` 
option and install it after that restart your PC and the issue should be resolved.

Last resort failing this sadly is a Factory reset, that helps many users get back online.