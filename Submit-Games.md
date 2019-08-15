## Sign Up and Enable Developer Mode

Submitting your game or app to SideQuest is super easy! All you have to do is sign up, enable developer mode and create your listing. 

You can sign up and create an account for Sidequest [here](https://sidequestvr.com/#/sign-up)

After creating an account, or if you already have just go to [Your Account](https://sidequestvr.com/#/account) and enable developer mode 

![](https://cdn.discordapp.com/attachments/608376262347587595/608596927466176542/Screenshot_1094.png)

Then set up your application in the app listings section. Add screenshots and a video to promote your work, the last screenshot will be used for the parallax banner at the top but will be hidden if there are no screenshots. 

![](https://cdn.discordapp.com/attachments/608376262347587595/608597561002950657/Screenshot_1095.png)
## Add an APK File URL
You can then add App urls or use Github Releases ( [Recommended](https://www.youtube.com/watch?v=B0IZv-ljwSI) ) to add a download option for your app/game.

![](https://cdn.discordapp.com/attachments/608376262347587595/608598066588680202/Screenshot_1096.png)

[Github Releases Video Tutorial](https://www.youtube.com/watch?v=B0IZv-ljwSI)

The Github Release workflow supports an auto-update pipeline for apps on SideQuest - a one time setup allows you to deploy app updates to users automatically when you publish a new release. If you don't use Github Releases you can still leverage the app update pipeline by incrementing the `Version Code` on your listing - this will trigger an update notification in the user's Dashboard. 


Warning: If you don't use Github Releases it is important to use a Direct Download URL, this means that the url should automatically download the APK file without any kind of confirmation/download option. This means google drive does not work but you can use dropbox if you change the file url slightly, for instance:

`https://www.dropbox.com/s/gsfgjg2g24gj42/MyCoolApp.apk` needs to have `?dl=1` added to the end so the full url is 
`https://www.dropbox.com/s/gsfgjg2g24gj42/MyCoolApp.apk?dl=1` which is then a direct download url. You can also use your own servers to host the app files or any facility that supports a direct download ( Glitch CDN, Github Repo Raw Link ).


You can also add all sorts of social/donate/info links with the App Urls section.

![](https://cdn.discordapp.com/attachments/608376262347587595/608599335587807242/Screenshot_1097.png)


## Fancy HTML Descriptions
You can use HTML in the description field, obviously things like forms don't work, and any Javascript or inline CSS is automatically sanitized. You can however use any CSS classes from the UI kit we use - https://materializecss.com/
![image](https://cdn.discordapp.com/attachments/591310408917450772/611690208768950272/unknown.png)
![image](https://cdn.discordapp.com/attachments/591310408917450772/611690319989178368/unknown.png)


## Promote your app with Events
You can also now create events to attract users and to promote your app Via the Dashboard
![](https://cdn.discordapp.com/attachments/608376262347587595/608596235712069644/Screenshot_1093.png)

Connect with us on [discord](https://discord.gg/hzCf9Vj) and ask for the `AD` (App Developer) role to get access to resources and feedback options on the developer process, and if you wish for your application to be put on the featured page just ping Shane Harrison on discord.