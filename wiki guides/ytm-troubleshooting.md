#**YT Music Troubleshooting**

(For troubleshooting help related to YT ReVanced Extended click [here](https://www.reddit.com/r/revancedextended/wiki/yt-troubleshooting/).)


#**Issues Within YT Music ReVanced Extended**

(See below for patching and installation troubleshooting.)




####**1. "org.schabi.newpipe is not installed."**

Follow the instructions in step 6 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_downloader_setup) to understand and set up the download function in YTM Extended.




####**2. I'm having issues signing in to my Google account**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).





####**3. No internet connection / The home page isn't loading**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).





####**4. Why can I only use the Radio feature?**

Google has made it so that Canadian (and possibly other countries') users that do not have YT Premium can only use the Radio feature within YouTube Music.

Follow the instructions in step 6 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_spoof_app_version_setup_.28for_canadian_users.29) to solve this.




####**5. How do I get YT Music ReVanced Extended on Android Auto?**

Follow the instructions in step 6 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_android_auto_setup).







#**Issues With Patching & Installation**



####**6. My device is not supported**

You'll most probably need to patch on a different Android device or on PC. Although you can try your luck with continuing the guide on your non-supported device.

If you patch on a different device or PC then make sure to patch the APK variant that was built for the architecture of the device you plan to **install** the patched APK on. See steps 2 and 3 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._revanced_manager_settings) for info on how to check and get the correct APK for the device you plan on installing YTM Extended on.

If you patch with the Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#wiki).



####**7. There are no apps or patches shown in the ReVanced Manager**

**a)** Ensure that you are using version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a version that is newer refer to step 1 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_1._downloading_the_revanced_manager_.26amp.3B_vanced_microg).

**b)** If you are on the correct Manager version and it's still not showing then it means that you did not change the Sources properly. Refer to step 2 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_2._revanced_manager_settings).




####**8. Nothing happens when I select the YTM APK from storage**

Make sure you are using version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a version that is newer refer to step 1 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_1._downloading_the_revanced_manager_.26amp.3B_vanced_microg). If you already are using the correct version, continue with the following steps:

**a)** Uninstall the official YouTube Music app.

**b)** Install the YouTube Music APK that you downloaded while following step 3 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_3._downloading_the_ytm_apk).

**c)** Open the ReVanced Manager > Patcher > Select an application > YouTube Music.

Continue from the middle of step 4 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_4._patching_the_apk).




####**9 Patcher is stuck on "Initializing..."**

The sources were not set properly. Refer to step 2 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_2._revanced_manager_settings).




####**10. Patcher is Aborting / Failing to apply patches**

If you see anywhere in the error "exit code = 135" or "exit code = 139" then follow the instructions in troubleshooting issue **#6**. If you don't see this error/exit code then continue with these 4 troubleshooting steps:

**a)** Make sure you are using version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a version that is newer refer to step 1 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_1._downloading_the_revanced_manager_.26amp.3B_vanced_microg).

**b)** Do not use a YTM version that is older than 5.21.52 or newer than 6.04.53. In general, it is best to use a version that was released prior to the most recent ReVanced Extended patch release. You can check when the last ReVanced Extended patch release was by clicking [here](https://github.com/inotia00/revanced-patches/releases/latest) and looking in the assets section.

**c)** Make sure to exclude the `Custom Branding Music Name` patch.

**d)** If your device's language was set to a language that reads right-to-left when the failure occurred then set your device's language to English or any language that reads left-to-right. Then fully close the Manager, and try again.

* If it still doesn't work then patch on a different device or PC. But make sure to patch the APK variant that was built for the architecture of the device you plan to **install** the patched APK on. See steps 2 and 3 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._revanced_manager_settings) for info on how to check and get the correct APK for the device you plan on installing YTM Extended on.

If you patch with the Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".

If you want to use a PC to patch then follow one of the PC methods in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#wiki).




####**11. "Error: Non-root install is not possible with the current patches selection."**

Patch again and include the `Music MicroG Support` patch.




####**12. "App not installed."**

**a)** If there was a google play protect pop-up when trying to install it then you must press **"More info"** and then tap the **"Install anyway"** button. If you press the "Got it" button it will not install. [Here](https://imgur.com/a/Ck8nfhn) is an image demonstrating this.

**b)** Ensure that you have ample available storage on your device.

**c)** Uninstall the YT Music ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or Private Folder that your device features.

**d)** If the error message was **"App not installed as app isn't compatible with your device."** then that means that the APK you patched doesn't match your device's architecture. Refer to steps 2 and 3 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._revanced_manager_settings).




####**13. "App not installed as package conflicts with an existing package."**

**a)** Uninstall the YT Music ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or Private Folder that your device features.

**b)** Open the ReVanced Manager > Patcher > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Make sure the package name starts with "app.rvx" like in [this image](https://imgur.com/a/AlYepUa). If it says something else, then you'll need to patch again, (using an unpatched APK,) and include the `Music MicroG Support` patch this time.

**c)** Create a detailed post if you are still having trouble.




####**14. "App not installed as package appears to be invalid."**

This error most often means that you are trying to install an app that is an older version than the already installed version. Android doesn't allow app downgrading. In the context of installing YTM Extended, here are some possible scenarios and solutions:

**a)** You are installing the unpatched YT Music APK that you downloaded from APKMirror.com. It is not necessary to install it. Refer to step 4 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_4._patching_the_apk) for info on selecting the YTM APK from storage.

**b)** Your patched YTM APK that you are installing was exported from the ReVanced Manager but does not have the `Music MicroG Support` patch applied to it. You can verify if this is the case by doing the following:

Open the ReVanced Manager > Patcher > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Check if the package name starts with "app.rvx" like in [this image](https://imgur.com/a/AlYepUa). If it says something else, then you'll need to patch again, (using an unpatched APK,) and include the `Music MicroG Support` patch this time.

**c)** You are installing a patched YTM Extended APK that is an older version than the YTM Extended that is currently installed. Uninstall YTM Extended before installing the older version.

**d)** You are installing an older version of Vanced MicroG than the one you already have installed. To uninstall the one you currently have installed, open your device Settings > Apps > Vanced MicroG > Uninstall.




####**15. "App not installed as app isn't compatible with your phone/tablet."**

You patched and installed a YT Music APK that was not built for your device's architecture. Refer to steps 2 and 3 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_2._revanced_manager_settings).




####**15. App crashes on startup**

3 common causes:

**a)** You do not have Vanced MicroG installed. Install the official [Vanced MicroG APK](https://github.com/TeamVanced/VancedMicroG/releases/latest) or you can use [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).

**b)** There was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#10** if this happened.

**c)** You patched and installed a YT Music APK that was not built for your device's architecture. Refer to steps 2 and 3 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._revanced_manager_settings).