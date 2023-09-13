##Troubleshooting Information 
.

**1. My device is ARMv7**

You'll need to patch on a different Android device or on PC.

When patching on a different device or PC be sure to patch the APK variant that was built for the architecture of the device you plan to **install** the patched APK on. Refer to step 2 in the guide for info on downloading an APK for a specific architecture.



**2. Patcher is aborting / failing to apply patches**

**a)** Make sure the ReVanced Manager is up to date. You can check and download the latest version from [here](https://github.com/revanced/revanced-manager/releases/latest).

**b)** Be sure to exclude all non-default patches.

**c)** Patches sometimes break in new YT Music versions. Try using an older YT Music version from Apkmirror.com. Refer to step 2 in the guide for some more info if you need.

**d)** Get help from the community. Post a screenshot of the full abort error in a new post, on the [ReVanced Discord server](https://discord.gg/revanced), or on the [ReVanced Telegram](https://t.me/app_revanced).


**3. "Error: Non-root install is not possible with the current patches selection."**

Patch again and include the `Vanced MicroG Support` patch.



**4. Manager is stuck saying "Installing..."**

Tap the save icon as shown in [this image](https://imgur.com/a/FKD0okE). Press "Save". Then go to your file manager and install the patched APK you just exported. You'll likely get an insallation error, so find and follow the troubleshooting entry for your errror below.



**5. "App not installed."**

Some scenerios and solutions:

**a)** If there was a google play protect pop-up when trying to install it then you **must** press **"More details"** and then tap the **"Install anyway"** button. If you press the "Got it" button it will not install. [Here](https://imgur.com/a/Ck8nfhn) is an image demonstrating this.

**b)** Ensure that you have ample storage on your device.

**c)** Follow the steps in issue **#6** directly below.



**6. "Error: App not installed as package conflicts with an existing package."**

Uninstall the YT Music ReVanced that is already on your device. Make sure that it's not installed in a different user profile or private folder that your device features.

The other possibility is that you are missing the `Vanced MicroG Support` patch. Patch again and include that patch. Make sure the patch applies successfully and doesn't fail.



**7. "App not installed as app isn't compatible with your device"**

The APK you patched doesn't match your device's architecture. Refer to step 2 in the guide for info on downloading an APK for a specific architecture.



**8. App crashes on startup**

Some possibilities:

**a)** You do not have Vanced MicroG installed. See step 1 of the guide.

**b)** You included a patch that is not recommended. Refer to step 3 in the guide. 

**c)**** There was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#2**.

**d)** The Google account you used to sign in has parental restrictions.



**9. I'm having issues signing in to my Google account**

The following instructions will solve most issues:

Device settings > Accounts > Vanced MicroG > Remove account. Then log in again. 

If this doesn't work then uninstall Vanced MicroG by going to device settings > Apps > Vanced MicroG > Uninstall. Then reinstall it.




**10. I'm from Canada. What do I need to know?**

Google has made it so that Canadian (and possibly other countries') users that do not have YT Premium can only use the Radio feature within YouTube Music. You can only listen to playlists that are made by the algorithm.

To get around this you can either use a VPN to a different country, an [old Vanced Music APK](https://www.apkmirror.com/apk/team-vanced/vanced-youtube-music/vanced-youtube-music-4-27-50-release/vanced-youtube-music-4-27-50-android-apk-download/), or you can get YTM ReVanced Extended, an unofficial alternative to YT Music ReVanced, which has a patch to circumvent this issue. [Here is the official YTM Extended guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/). Be sure to follow the special instructions for Canadian users when following the guide.



**. Why can I only use the Radio feature?**

Refer to issue **#10** directly above this.