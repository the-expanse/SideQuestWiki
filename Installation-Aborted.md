if you have installed SideQuest utilizing a ZIP folder and not the EXE installer SideQuests auto updater will have issues the next time an update to SideQuest is released as it tries to uninstall the current version and update it but no uninstaller exists with the Portable ZIP version of SideQuest, the solution is simply to delete all of SideQuest and associated folders then install the newest proper EXE version of the SideQuest Store from [SideQuest EXE Installers](https://sidequestvr.com/#/download)

You can also use the [Force uninstaller](https://github.com/the-expanse/SideQuest/wiki/Force-Uninstaller-for-SideQuest#sidequest-clean-force-uninstaller) which should clean out any folders and files that are causing issues with updating or reinstalling SideQuest


Else you can manually delete these folders.
###### be sure to replace `YOUR USERNAME` with your own computer accounts user name

`C:\Users\YOURUSERNAME\AppData\Local\sidequest-updater`

![](https://cdn.discordapp.com/attachments/615234122604085262/628991406450540554/Screenshot_402.png)

`C:\Users\YOURUSERNAME\AppData\Local\Programs\SideQuest`

![](https://cdn.discordapp.com/attachments/615234122604085262/628991405078872074/Screenshot_403.png)

`C:\Users\YOURUSERNAME\AppData\Roaming\SideQuest`
![](https://cdn.discordapp.com/attachments/615234122604085262/628991405058162698/Screenshot_404.png)

Note that `C:\Users\USERNAME\AppData\Roaming\SideQuest` also may hold any old backups, you may be able to save these backups by not deleting the folder, and after install setting the backup folder to `C:\Users\USERNAME\AppData\Roaming\SideQuest` under `My Apps` backups tab
