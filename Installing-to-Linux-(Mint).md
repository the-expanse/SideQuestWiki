If you see 
`Warning: no permissions. ADB udev rules missing`

Try the below and it may help connect.

First off to install adb type in

'sudo apt install adb'
Then create a rule
`/etc/udev/rules.d/50-oculus.rules`

SUBSYSTEM="usb", ATTR{idVendor}=="2833", ATTR{idProduct}=="0186", MODE="0660" group="plugdev", symlink+="ocuquest%n"

Kill and restart the server a few times

`sudo adb kill-server`

Then

`sudo adb start-server`
Respectively 

And finally type in

`sudo adb devices`

You may have to run `sudo adb devices` to restart the device connection on reboot but it should work. If not you can see our discord for possible direct help.