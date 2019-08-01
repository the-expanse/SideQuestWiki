Having connection issues?
First things first: try a different USB. If you have a phone USB cable that fits use that. Also try a different USB port. This solves 90% of problems with ADB connection issues, if your using Bluestacks, a Wifi Extender or a VPN best to refrain from them as they are all known to cause issues, always try to connect directly to the same router as your pc or phone, or just only install and manage songs in headset to avoid issues

This next bit could be tricky, you have to open `cmd` or Command Prompt. 
( If your on mac then click the wrench icon in the top right and click "open adb folder" - then drag this onto a terminal window )

Type this `cd %appdata%\SideQuest\platform-tools\`<br>
Then type this `adb devices`<br>

You should see:
```
List of devices attached
1SOTGDHHSD93  device
```

If you see `1SOTGDHHSD93  unauthorized` - put on your headset now you should see the message to allow usb debugging - click always allow. 

if you see  `1SOTGDHHSD93  offline` - then type `adb kill-server` and then `adb devices` again.

if you see `cannot connect to daemon` then open up task manager and kill the `adb.exe` process - `taskkill /f /im adb.exe`