Having connection issues?
First things first: try a different USB. If you have a phone USB cable that fits use that. Also try a different USB port. This solves 90% off problems so far. 

This next bit could be tricky, you have to open `cmd` or Command Prompt. 
( If your on mac then click the wrench icon in the top right and click "open adb folder" - then drag this onto a terminal window )
Type this `cd %appdata%\SideQuest\platform-tools\`
Then type this `adb devices`
You should see:```List of devices attached
1SOTGDHHSD93  device```

If you see `1SOTGDHHSD93  unauthorized` - put on your headset now you should see the message to allow usb debugging - click always allow. 

if you see  `1SOTGDHHSD93  offline` - then type `adb kill-server` and then `adb devices` again.

if you see `cannot connect to daemon` then open up task manager and kill the `adb.exe` process - `taskkill /f /im adb.exe`