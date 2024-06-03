Info
=
This guide was updated on May 30th, 2024. Things may have changed from when you last read it.

If needed, you can ask for assistance in the ReVanced [Discord](https://discord.com/invite/revanced), [Subreddit](https://www.reddit.com/r/revancedapp/), or [Telegram](https://t.me/revanced_topics/3192).


Client ID Setup
=

Go to [this page](https://www.reddit.com/prefs/apps) (and sign in to the Reddit account you want to use).

Select `are you a developer? Create an app`.

![are-you-a-developer-create-an-app](https://github.com/KobeW50/ReVanced-Documentation/blob/main/images/reddit-client-id-guide/are-you-a-developer-create-an-app.jpg)

1. Enter an app name (it doesn't matter what you call it).

2. Set the type to "installed app".

3. Set the "**redirect uri**" according to this table:

| App | Redirect URI |
|---|---|
| Sync | `http://redditsync/auth` |
| Boost | `http://rubenmayayo.com` |
| Infinity | `infinity://localhost` |
| RIF | `redditisfun://auth` |
| Relay | `dbrady://relay` |
| Slide | `http://www.ccrama.me` |
| BaconReader | `http://baconreader.com/auth` |
| Joey | `https://127.0.0.1:65023/authorize_callback` |

> Don't add a `description` or `about url`.

(Many users experience rate limits while using patched Boost.)

4. Press `create app`.

![create-application](https://github.com/KobeW50/ReVanced-Documentation/blob/main/images/reddit-client-id-guide/create-application.jpg)

5. Copy the client ID, which is directly under the app name. Save it in your clipboard. You'll need it soon.

![copy-client-id](https://github.com/KobeW50/ReVanced-Documentation/blob/main/images/reddit-client-id-guide/copy-client-id.jpg)

> (**Optional**): If you want to be able to sign in to the patched app with Reddit accounts aside from the one that the client ID is under you must add those accounts as developers to the application you just made. To add a developer, enter the username (without the "u/") of the account to add in the `add developer:` field and press **Enter** on your keyboard. Then press the `update app` button.
>
> ![add-developer](https://github.com/KobeW50/ReVanced-Documentation/blob/main/images/reddit-client-id-guide/add-developer.jpg)
>
> (If you don't see the `add developer:` field, press the `edit` button in the bottom-left.)
> 
> <img src="https://github.com/KobeW50/ReVanced-Documentation/blob/main/images/reddit-client-id-guide/edit-button.jpg" alt="edit-button" width="400"/>


Patching Setup

Uninstall the official version of the app you are going to patch. (Example: If you have Sync installed, and are about to patch Sync, uninstall the Sync app.)

You may want to export the settings configuration from your reddit client app before uninstalling.

Install (or update to) the latest version of the ReVanced Manager.


Download the APK

Do not install the APK after you download it!

Sync download

Boost download 

Relay download

Reddit is Fun (RIF) download

BaconReader download

Infinity download

Slide download

Joey download from apkmonk.com (If you use the latest version there will be a popup that will only stop appearing after you click on  “Learn More & Register”)

Do not install the APK after you download it!

Open the Manager > Patcher > Select an application.

Press the “Storage” button and then select the APK file that you downloaded.

Tap on the “Selected patches” card.


(Most Reddit clients only have the Spoof Client patch.)



Tap on the “Default” button and then press the gear icon by the Spoof client patch.



Enter the client ID that you copied earlier and then press “Save”. Make sure there are no extra spaces.



Press “Done” and then “Patch” and wait for it to finish.

(optional) If you want to save or share the patched APK file, you can export it by using the save button in the bottom left corner.

Install the patched APK.

If you get a pop-up from Google Play Protect while installing, press “More details” and then press “Install anyway”.



Import the settings backup into your patched Reddit client app (if you created a backup earlier).

Done!

(If needed, you can ask for assistance in the ReVanced Discord, Subreddit, or Telegram.)


Multiple Users

If you want to add multiple accounts to your patched app, go back to this page and edit the developed application. Then add your other username as a developer and press Enter on the keyboard. Then press the update button.








Basic Troubleshooting



If you get the error pictured above, enter in your credentials manually instead of pasting or auto-entering it.

Other errors when signing in

This usually means that something is wrong with your client ID configuration. Here are some common mistakes:

If you are certain that you do not have any of the issues below, create a new client ID and try again from scratch.

The redirect URI is not EXACTLY as shown (maybe it has an extra "/", a capital letter, or you put “https” instead of “http” or vice versa.)

The app type is not set to “Installed app”.

You accidentally added an extra space when entering the client ID in the Manager.

The redirect URI is set for a different application. (Example: it is set to “http://redditsync/auth” even though the client ID will be used for an app other than Sync.)
