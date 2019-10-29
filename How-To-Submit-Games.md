## Sign Up and Enable Developer Mode

Submitting your game or app to SideQuest is super easy! Sign up and be ready to submit your app within minutes. Apps are approved on the first submit but can be updated after that without approval. We have a great relationship with our community of developers so if you have any issues please reach out on [Discord](https://discord.gg/HNnDPSu) or on [SideQuest](https://sidequestvr.com/#/account/message-thread/1). 

You can sign up and create an account for Sidequest [here](https://sidequestvr.com/#/sign-up)

After creating an account, Head to [Your Account](https://sidequestvr.com/#/account) and enable developer mode as shown below

![](https://cdn.discordapp.com/attachments/615234075778875453/622156586365747210/Screenshot_236.png)

Then set up your app listing as shown below.

![](https://i.imgur.com/Vd2DrFK.png)

![](https://i.imgur.com/DtFBePK.png)

Try to add screenshots and a video to promote your work, the last screenshot is used as the parallax banner at the top. 

## SelfHost - Supply an APK URL
You can supply a download url for your APK file under the App Urls section of the listing editor. Select the type `APK` in the drop down. If you update your app you can increase the Version Code on the listing to trigger auto-updates for users of your app. It is important to make sure it is a [Direct Download Url](https://github.com/the-expanse/SideQuest/wiki/How-To-Submit-Games#direct-download-warning)

![](https://i.imgur.com/ULJiU6U.png)


## Deploy to Github Releases
Here is a video tutorial on setting up an automated workflow with github releases. You can use an empty repository.
[![](https://cdn.discordapp.com/attachments/608376262347587595/611697801360834600/Screenshot_10.png)](https://www.youtube.com/watch?v=B0IZv-ljwSI)

The Github Release workflow also supports auto-updates for apps on SideQuest - a one time setup allows you to deploy app updates to users automatically when you publish a new release to GitHub.



## CI/CD without Github Releases
If you use another CI/CD workflow that does not involve Github Releases then you can use the following webhook to trigger auto-updates for users:

Copy the webhook url like normal here -
![image](
https://cdn.discordapp.com/attachments/638666189039730690/638666413728464906/unknown.png)
Which gives you `https://xpan.cc/release-webhook/BIG_LONG_TOKEN`
Change it to `https://xpan.cc/version-webhook/VERSION_CODE/BIG_LONG_TOKEN`

Just replace `VERSION_CODE` with your incremented version code and leave the `BIG_LONG_TOKEN` the same as the webhook url you copied. It accepts GET and POST requests and you can also optionally include a JSON payload with the url property to also update the URL of the APK file. It will remove any existing app urls with type `APK` and add the new one specified in the JSON payload. 

Here is a sample curl request:

```bash
curl -X POST \
  https://xpan.cc/version-webhook/VERSION_CODE/BIG_LONG_TOKEN \
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



## Direct Download Warning
It is important to use a Direct Download URL, meaning that if your URL is copied and pasted into a browser should automatically download the APK, and do so without any kind of confirmation screen. Google Drive does not work for this reason however you can use Dropbox if you change the file URL slightly as it makes it a direct download URL, for instance:

`https://www.dropbox.com/s/gsfgjg2g24gj42/MyCoolApp.apk`

requires you to accept, but if you add `?dl=1` to the end so the full URL is 

`https://www.dropbox.com/s/gsfgjg2g24gj42/MyCoolApp.apk?dl=1`

it becomes a direct download URL.

You can also use your own servers to host the app files or any facility that supports a direct download ( Glitch CDN, GitHub Repo Raw Link ). Add a URL of type APK in the app URLs section. 

![](https://cdn.discordapp.com/attachments/615234075778875453/622159882862460928/Screenshot_241.png)

You can also add all sorts of social/donate/info links with the App URLs section from this page for things like app promotion.




## Promote your app even further with Events
You can create events with scheduled times that users can subscribe to in order to promote your app, this can easily be done in your user Dashboard as shown below.
![](https://i.imgur.com/V19jKpj.png)

Connect with us on [Discord](https://discord.gg/hzCf9Vj) and ask for the `AD` (App Developer) role to get access to resources and feedback options on the developer process, and if you wish for your application to be put on the featured page just ping Shane Harris on discord.