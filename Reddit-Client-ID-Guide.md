# Guide to patch Reddit clients

Info
=

- For this process, you will need an Android device running Android 8 or newer

- The last significant update to this guide was on July 27th, 2024

- This guide is **not** for patching the regular Reddit app. It is only for patching 3rd party Reddit clients (Sync, Infinity, RIF, etc.)

- If needed, you can ask for assistance in the ReVanced [Discord](https://discord.com/invite/revanced), [Subreddit](https://www.reddit.com/r/revancedapp/), or [Telegram](https://t.me/revanced_topics/3192). There is also troubleshooting info at the end of this guide



Client ID Setup
=

**1.** Go to [this page](https://www.reddit.com/prefs/apps) (and sign in to the Reddit account you want to use).

**2.** Select `are you a developer? Create an app`.

<img src="/images/reddit-client-id-guide/are-you-a-developer-create-an-app.jpg" width="800"/>


**3.** Enter an app name (it doesn't matter what you call it).

**4.** Set the type to "installed app".

> [!WARNING] 
> Don't add a `description` or `about url`.

**5.** Set the **`redirect uri`** according to this table:

| App | Redirect URI |
|---|---|
| Sync | `http://redditsync/auth` |
| Infinity / Infinity+ | `infinity://localhost` |
| RIF | `redditisfun://auth` |
| Boost | `http://rubenmayayo.com` |
| Relay | `dbrady://relay` |
| Slide | `http://www.ccrama.me` |
| BaconReader | `http://baconreader.com/auth` |
| Joey | `https://127.0.0.1:65023/authorize_callback` |

> [!TIP]
>
> If you plan to use Slide, consider trying [this fork](https://github.com/cygnusx-1-org/Slide/releases/latest) of the app, which is still being maintained and does not require [patching](#Patching). After obtaining a client ID, simply enter it into the textbox when you open the app. See the [setup instructions](https://github.com/cygnusx-1-org/Slide/blob/master/docs/SETUP.md) for more info.

**6.** Press `create app`.

<img src="/images/reddit-client-id-guide/create-application.jpg" width="400"/>


**7.** Copy the client ID, which is directly under the app name. Save it in your clipboard. You'll need it soon.

<img src="/images/reddit-client-id-guide/copy-client-id.jpg" width="400"/>


> [!TIP]
> If you want to be able to sign in to the patched app with Reddit accounts aside from the one tied to the client ID, you must add the accounts as developers to the application you just made.
>
> To add a developer, edit the application and enter the account username in the `add developer:` field. Press **`Enter`** on your keyboard and then press the `update app` button.
>
> <img src="/images/reddit-client-id-guide/adding-developer.gif"/>



Patching
=

**1.** Uninstall the official version of the app you will patch. 

> Example: If you have Sync installed and are about to patch Sync, uninstall the Sync app.

> [!TIP] 
> Remember to export your settings configuration before uninstalling (if your Reddit client has the option).

**2.** Install (or update to) the latest version of the [ReVanced Manager](https://revanced.app/download).

**3.** Download (but do **not** install) an APK of the app you want to patch using the link:

- [Sync download](https://www.apkmirror.com/apk/red-apps-ltd/sync-for-reddit/sync-for-reddit-v23-06-30-1339-release/sync-for-reddit-v23-06-30-1339-2-android-apk-download/)

- [Infinity+ download](https://github.com/Docile-Alligator/Infinity-For-Reddit/releases)

  <details>
  <summary><strong>Info for Infinity(+) users</strong></summary>
  <br>

  The above link points to the latest Infinity+ GitHub release.
  
  If patching errors occur (in step 9 of this guide), use an older Infinity+ version, such as [7.4.3](https://github.com/Docile-Alligator/Infinity-For-Reddit/releases/tag/v7.4.3) (which I have tested).
  </details>

- [Reddit is Fun (RIF) download](https://www.apkmirror.com/apk/talklittle/reddit-is-fun/reddit-is-fun-5-6-22-release/rif-is-fun-for-reddit-5-6-22-android-apk-download/)

- [Boost download](https://www.apkmirror.com/apk/ruben-mayayo/boost-for-reddit/boost-for-reddit-1-12-12-release/boost-for-reddit-1-12-12-android-apk-download/)

- [Relay download](https://www.apkmirror.com/apk/dbrady/relay-for-reddit-2/relay-for-reddit-2-10-2-40-release/relay-for-reddit-10-2-40-android-apk-download/)

- [Slide download](https://www.apkmirror.com/apk/haptic-apps/slide-for-reddit/slide-for-reddit-6-7-1-release/slide-for-reddit-6-7-1-2-android-apk-download/)

  <details>
  <summary><strong>Info for Slide users</strong></summary>
  <br>

  If you plan to use Slide, consider trying [this fork](https://github.com/cygnusx-1-org/Slide/releases/latest) of the app, which is still being maintained and does not require patching. Simply enter the client ID into the textbox when you open the app. See the [setup instructions](https://github.com/cygnusx-1-org/Slide/blob/master/docs/SETUP.md) for more info.
  </details>

- [BaconReader download](https://www.apkmirror.com/apk/onelouder-apps/baconreader-for-reddit/baconreader-for-reddit-6-1-4-release/baconreader-for-reddit-6-1-4-android-apk-download/)

- [Joey download (from apkmonk.com)](https://www.apkmonk.com/app/o.o.joey/)

> [!WARNING]
> Do not install the APK after you download it.

**4.** Launch the ReVanced Manager and go to the settings. Enable `Allow changing patch selection`. Then, go to the Patcher tab and tap `Select an application`.

**5.** Press the `Storage` button and select the APK file that you downloaded.

<img src="/images/reddit-client-id-guide/storage-button.png" width="400"/>


**6.** Tap on the `Selected patches` card.

<img src="/images/reddit-client-id-guide/selected-patches.png" width="400"/>


**7.** Press the `Default` button and then press the ⚙️ icon by the "Spoof client" patch.

<img src="/images/reddit-client-id-guide/default-patches.jpg" width="400"/>


**8.** Enter the client ID that you copied earlier and then press `Save`. Make sure there are no extra spaces.

<img src="/images/reddit-client-id-guide/client-id-patch-option.jpg" width="400"/>


**9.** Press `Done` and then `Patch`, and then wait for it to finish.

**10.** After patching is complete, press the `Install` button.

> [!IMPORTANT]
> If you get a popup from Google Play Protect while installing, press `More details` and then press `Install anyway`.
>
> <img src="/images/reddit-client-id-guide/install-anyway.jpg" width="400"/>


> [!TIP]
> If you want to save or share the patched APK file, you can export it by using the save button in the bottom left corner (opposite the `Install` button).

Done!



Troubleshooting
=

### 1. "Please match the requested format." error when signing in

<img src="/images/reddit-client-id-guide/credentials-format-error.jpg" width="400"/>

If you get the error pictured above, enter your username and password manually instead of pasting or auto-entering them.

### 2. Errors when signing in

Sign-in errors usually mean that something is wrong with your client ID configuration. Below are some common mistakes. 

> [!NOTE]
> If you are certain that none of the issues below apply to you, create a new client ID and try again from scratch, or ask for assistance in the ReVanced [Discord](https://discord.com/invite/revanced), [Subreddit](https://www.reddit.com/r/revancedapp/), or [Telegram](https://t.me/revanced_topics/3192).

**a)** The `redirect uri` is not EXACTLY the same as in the table above. Correct the issue [here](https://www.reddit.com/prefs/apps).

> [!TIP]
> Check if in the `redirect uri` you put `https` instead of `http` (or vice versa), a capital letter, an extra `/`, etc.

**b)** The app type is not set to `installed app`. Correct the issue [here](https://www.reddit.com/prefs/apps).

**c)** You accidentally added an extra space when entering the client ID in the ReVanced Manager. You must repatch, but you don't need to set up a new client ID.

**d)** The `redirect uri` is set for the wrong app. Correct the issue [here](https://www.reddit.com/prefs/apps).

> Example: It is set to `http://redditsync/auth` even though the client ID will be used for an app other than Sync.
