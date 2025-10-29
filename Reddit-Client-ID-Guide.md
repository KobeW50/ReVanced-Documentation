# Guide to patch Reddit clients

Info
=

- The last **significant** update to this guide was on Oct 29th, 2025

- For this process, you will need an Android device running Android 8 or newer

- This guide is **not** for patching the regular Reddit app. It is only for patching 3rd party Reddit clients (Sync, Infinity, RIF, etc.)

- If needed, you can ask for assistance in the ReVanced [Discord](https://discord.com/invite/revanced), [Subreddit](https://www.reddit.com/r/revancedapp/), or [Telegram](https://t.me/revanced_topics/3192). There is also [troubleshooting info](#Troubleshooting) at the end of this guide



Client ID Setup
=

**1.** Go to [this page](https://www.reddit.com/prefs/apps) (and sign in to the Reddit account you want to use).

**2.** Select `are you a developer? Create an app...`.

<img src="/images/reddit-client-id-guide/are-you-a-developer-create-an-app.jpg" width="720"/>


**3.** Enter an app name (it doesn't matter what you call it).

**4.** Set the type to `installed app`.

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

<img src="/images/reddit-client-id-guide/create-app.jpg" width="349"/>


**7.** Copy the client ID, which is directly under the app name. Save it in your clipboard. You'll need it soon.

<img src="/images/reddit-client-id-guide/copy-client-id.jpg" width="366"/>


> [!TIP]
> If you want to be able to sign in to the patched app with Reddit accounts aside from the one tied to the client ID, you must add the accounts as developers to the application you just made.
>
> To add a developer, edit the application and enter the account username in the `add developer:` field. Press <kbd>Enter</kbd> on your keyboard and then press the `update app` button.
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
  
  If patching errors occur (in step 10 of this guide), use an older Infinity+ version, such as [8.0.7](https://github.com/Docile-Alligator/Infinity-For-Reddit/releases/tag/v8.0.7) (which I have tested).
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

- Joey: Unfortunately, Joey is not available on apkmirror or GitHub. I do not trust any other sites that distribute the APK, so you'll need to find an APK on your own if you want to use Joey.

> [!WARNING]
> Do not install the APK after you download it.

**4.** Open ReVanced Manager. If prompted, grant ReVanced Manager permission to install unknown apps and to run in the background.

**5.** From the Apps tab, press the `+` button in the bottom right corner.

<img src="/images/reddit-client-id-guide/add-an-app.jpg" width="270"/>


**6.** Press `Select from storage` and select the APK file you downloaded.

<img src="/images/reddit-client-id-guide/select-from-storage.jpg" width="360"/>


**7.** Tap `Select patches`.

<img src="/images/reddit-client-id-guide/select-patches.jpg" width="360"/>


**8.** Press the **`⟲`** button and then press the **`⛭`** button by the `Spoof client` patch.

<img src="/images/reddit-client-id-guide/default-patches.jpg" width="360"/>


**9.** Enter the client ID that you copied earlier. Make sure there are no extra spaces. Then, press `Save` and return to the patch selection menu.

<img src="/images/reddit-client-id-guide/client-id-patch-option.jpg" width="360"/>


> [!TIP]
> If using Infinity+ or Relay, updates for the app will appear in Google Play Store. To learn how to avoid this nuisance, see the footnotes.[^1]

**10.** Press `Save` and then `Patch`. Keep ReVanced Manager open while the app is being patched. Make sure no errors occur.

**11.** When patching completes, press `Install`.

> [!IMPORTANT]
> If you get a popup from Google Play Protect while installing, press `More details` and then press `Install anyway`.
>
> <img src="/images/reddit-client-id-guide/install-anyway.jpg" width="323"/>

> [!TIP]
> You can also export the patched APK file using the save button on the bottom left.

Done!



Troubleshooting
=

### 1. "Please match the requested format." error when signing in

<img src="/images/reddit-client-id-guide/credentials-format-error.jpg" width="350"/>

If you get the error pictured above, enter your username and password manually instead of pasting or auto-entering them.


### 2. Correct username and password does not work

There are two known cases where this issue occurs:

**Case 1**: This issue can occur due to an outdated Android System Webview. Install or update [Android System Webview](https://play.google.com/store/apps/details?id=com.google.android.webview).

> If you can't access Android System Webview normally through Google Play Store, open your device's settings > Apps, and search for Android System Webview. Then, find the option to view it in Google Play Store.

**Case 2**: In Reddit is Fun (RIF) and possibly other clients, this issue sometimes occurs when logging in from certain countries. You can use a VPN (such as [ProtonVPN](https://play.google.com/store/apps/details?id=ch.protonvpn.android), which has a free tier,) to connect from another country and then log in.


### 3. Other errors when signing in

Sign-in errors usually mean that something is wrong with your client ID configuration. Below are some common mistakes. 

> [!NOTE]
> If you are certain that none of the issues below apply to you, create a new client ID and try again from scratch, or ask for assistance in the ReVanced [Discord](https://discord.com/invite/revanced), [Subreddit](https://www.reddit.com/r/revancedapp/), or [Telegram](https://t.me/revanced_topics/3192).

**Mistake A:** The `redirect uri` is not EXACTLY the same as in the table above. Correct the issue [here](https://www.reddit.com/prefs/apps).

> [!TIP]
> Check if in the `redirect uri` you put `https` instead of `http` (or vice versa), a capital letter, an extra `/`, etc.

**Mistake B:** The app type is not set to `installed app`. Correct the issue [here](https://www.reddit.com/prefs/apps).

**Mistake C:** You accidentally added an extra space when entering the client ID in the ReVanced Manager. You must repatch, but you don't need to set up a new client ID.

**Mistake D:** The `redirect uri` is set for the wrong app. Correct the issue [here](https://www.reddit.com/prefs/apps).

> Example: It is set to `http://redditsync/auth` even though the client ID will be used for an app other than Sync.

___
[^1]: To avoid having an update for the patched client appear in Google Play Store, include the `Change version code` patch when patching the app. Make sure that the `Version code` patch option for this patch is set to "Highest" (2147483647). Note that in order for this patch to be visible in the patch selection menu, you need to enable `Show universal patches` in the Advanced section of the ReVanced Manager settings. You will also need to enable `Allow changing patch selection and options` in the same settings menu. Additionally, note that if you ever want to update the app instance, you will need to include the `Change version code` patch again or do a fresh install.
