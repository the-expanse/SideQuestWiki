Submitting your game or app to SideQuest is super easy! Sign up and be ready to submit your app within minutes. Apps are approved on the first submit but can be updated after that without approval. We have a great relationship with our community of developers so if you have any issues please reach out on [Discord](https://discord.gg/HNnDPSu) or on [SideQuest](https://sidequestvr.com/#/account/message-thread/1). 

## Index
[Sign Up and Enable Developer Mode](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#sign-up-and-enable-developer-mode)

[Listing Best Practices](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#listing-best-practices)

[Featured Listings](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#featured-listings)

[SelfHost/Itch.io - Supply an APK/Itch URL](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#selfhostitchio---supply-an-apkitch-url)

[Deploy to Github Releases](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#deploy-to-github-releases)

[CI/CD without Github Releases](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#cicd-without-github-releases)

[Promote your Social Media and App Store Pages](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#promote-your-social-media-and-app-store-pages)

[Direct Download](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#direct-download)


## Sign Up and Enable Developer Mode


You can sign up and create an account for Sidequest [here](https://sidequestvr.com/#/sign-up)

After creating an account, Head to [Your Account](https://sidequestvr.com/#/account) and enable developer mode as shown below

![](https://i.imgur.com/809Ft7i.png)

Then set up your app listing as shown below.

![](https://i.imgur.com/LWSmgf2.png)

![](https://i.imgur.com/s5dTGqQ.png)

Try to add screenshots and a video to promote your work, the last screenshot is used as the parallax banner at the top. 

## Listing Best Practices

It is important to represent your work as best you can in the listing, this is vital to be able to convert people from viewers into users who download your content. As SideQuest grows it will become increasingly difficult to get exposure so having a well laid out listing is important if you want to catch the attention of users. We are always eager to promote your work and we will feature developers on the home page of SideQuest for free upon request, but its important to create a lasting impression once they get to your app listing page. Below is one of the finest examples of an app listing on SideQuest that really demonstrates an engaging piece of content giving it the best possibly chances of catching the users eye. Add a video, use a high quality image for the top banner, add some structure to your description ( html supported ) to really make it shine!

This listing was made by [VictoryXR](https://sidequestvr.com/#/user/102517). Click to see other listings too for more great ideas.

![i](https://i.imgur.com/KoN9IkX.png)

## Featured Listings

At SideQuest we do not yet offer paid advertising for developers, mainly because we want to be able to offer everyone a chance to get some extra promotion and not just those that can afford to pay the most. If you want to be featured on the homepage banner/slider then just reach out to me and ill add you into the schedule. There can sometimes be a backlog so it might be worthwhile to reach out at least a week in advance to secure your spot if you want to coordinate it with a release. Here are some good examples of banner images and how they look on desktop and mobile platforms.


Mobile view          |  Desktop View
:-------------------------:|:-------------------------:
![i](https://i.imgur.com/7HXhh1d.png)  |  ![i](https://i.imgur.com/jCxQHcp.png)


## SelfHost/Itch.io - Supply an APK/Itch URL
You can supply a download url for your APK file under the App Urls section of the listing editor. Select the type `APK` in the drop down. If you update your app you can increase the Version Code on the listing to trigger auto-updates for users of your app. It is important to make sure it is a [Direct Download Url](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#direct-download). If you want to link to an existing itch listing, just supply the itch.io listing page. SideQuest can install APK files or ZIP files from itch.io ( all APK + OBB files inside the zip ). 

![](https://i.imgur.com/SzHTXwO.png)


## Deploy to Github Releases
![i](https://i.imgur.com/MWryZis.png)
You also need to setup a webhook on github to send a release notification to SideQuest. See the below video tutorial for more information. 
[Video Tutorial](https://www.youtube.com/watch?v=B0IZv-ljwSI)

The Github Release workflow also supports auto-updates for apps on SideQuest - a one time setup allows you to deploy app updates to users automatically when you publish a new release to GitHub. You can use an empty repository.



## CI/CD without Github Releases
If you use another CI/CD workflow that does not involve Github Releases then you can use the following webhook to trigger auto-updates for users:

Copy the webhook url like normal here -
![image](
https://i.imgur.com/wSSgmZo.png)

Which gives you 
`https://sdq.st/release-webhook/BIG_LONG_TOKEN`

Change it to 
`https://sdq.st/version-webhook/VERSION_CODE/BIG_LONG_TOKEN`

Just replace `VERSION_CODE` with your incremented version code and leave the `BIG_LONG_TOKEN` the same as the webhook url you copied. It accepts GET and POST requests and you can also optionally include a JSON payload with the url property to update the URL of the APK file. It will remove any existing app urls with type `APK` and add the new one specified in the JSON payload. 

Here is a sample curl request:

```bash
curl -X POST \
  https://sdq.st/version-webhook/VERSION_CODE/BIG_LONG_TOKEN \
  -H 'Accept: */*' \
  -H 'Accept-Encoding: gzip, deflate' \
  -H 'Cache-Control: no-cache' \
  -H 'Connection: keep-alive' \
  -H 'Content-Length: 25' \
  -H 'Content-Type: application/json' \
  -H 'Host: xpan.cc' \
  -H 'cache-control: no-cache' \
  -d '{
  "url": "http://www.example.com"
}'
```


## Promote your Social Media and App Store Pages
If your app is already on Desktop or Mobile VR stores such as Oculus Go/Quest/Rift, Steam, Viveport, Epic then include links to those pages also. 

![](https://i.imgur.com/w6Ppp4p.png)

You can also add all sorts of social/donate/info links with the App URLs section from this page for things like app promotion.



## Direct Download
It is important to use a Direct Download URL, meaning that if your URL is copied and pasted into a browser should automatically download the APK, and do so without any kind of confirmation screen. Google Drive does not work for this reason however you can use Dropbox if you change the file URL slightly as it makes it a direct download URL, for instance:

`https://www.dropbox.com/s/gsfgjg2g24gj42/MyCoolApp.apk`

requires you to accept, but if you add `?dl=1` to the end so the full URL is 

`https://www.dropbox.com/s/gsfgjg2g24gj42/MyCoolApp.apk?dl=1`

it becomes a direct download URL.

