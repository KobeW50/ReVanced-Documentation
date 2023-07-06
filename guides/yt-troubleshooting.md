#**YT ReVanced Extended Troubleshooting**

(For troubleshooting help related to YT **Music** Extended click [here](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/).)



#**Issues Within YT ReVanced Extended**

(See below for patching and installation troubleshooting.)



####**1. No internet connection / The home page isn't loading**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




####**2. I'm having issues signing in to my Google account**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




####**3. "ussr.razar.youtube_dl is not installed. Please install it."**

Follow the instructions in step 6 of the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_downloader_setup) to understand and set up the download function in YT ReVanced Extended.




####**4. Videos stop and buffer when they hit 1:09**

There are 3 workarounds for this issue.

**1)** Use a different Google account.

**2)** Use Incognito mode (in the app).

**3)** Spoof to version `16.08.35`. To spoof, open YT ReVanced Extended and tap the profile picture > Settings > ReVanced Extended > Miscellaneous > Spoof app version, **On**. Then restart the app.

Open YT ReVanced Extended again and tap the profile picture > Settings > ReVanced Extended > Miscellaneous > Spoof app version target > 16.08.35. Then restart the app.

If you do not see the options to Spoof the app version or select the app version target, patch a new YT ReVanced Extended APK and include the `Spoof App Version` patch. After it is installed you will be able to follow the steps above.




####**5. Videos stop and buffer (at no specific point)**

If your issue is not issue **#4** above, patch a new YouTube ReVanced Extended APK and include the `Protobuf Spoof` patch. Then after it is installed, navigate to Settings > ReVanced Extended > Miscellaneous > Enable protobuf spoof, **On**. Press "Restart". It should now work.

Alternatively, there are 2 other workarounds for this issue.

**1)** Use a different Google account.

**2)** Use Incognito mode (in the app).




####**6. YouTube Shorts and/or the Shorts button is gone**

**To unhide Shorts in feeds:**

Go to Settings > ReVanced Extended > Shorts > Hide shorts shelf, **Off**.

**To unhide the Shorts button:**

Go to Settings > ReVanced Extended > Navigation > Hide shorts button, **Off**.




####**7. The player UI doesn't go away**

**a)** Make sure you don't have it set to never go away in the Accessibility settings. To check, navigate to Settings > Accessibility. Either disable accessibility settings or lower the timer so that it goes away sooner.

**b)** If that wasn't the issue, simply close and restart the app.




####**8. SponsorBlock is not working**

This likely means that the SponsorBlock servers are down. You can check the server status [here](https://status.sponsor.ajay.app/).




####**9. Watch history isn't being saved on YouTube**

Whitelist `s.youtube.com` in your ad-blocker.







#**Issues With Patching & Installation**


####**10. My device is not supported**

You'll most probably need to patch on a different Android device or on PC. Although you can try your luck with continuing the guide on your non-supported device.

If you patch with the Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#wiki).




####**11. There are no apps or patches shown in the ReVanced Manager**

**a)** Ensure that you are using version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a version that is newer refer to step 1 of the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_1._downloading_the_revanced_manager_.26amp.3B_vanced_microg).

**b)** If you are on the correct Manager version and it's still not showing then it means that you did not change the Sources properly. Refer to step 2 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._revanced_manager_settings).




####**12. "Feature not implemented: This application is a split APK and cannot be selected."**

On non-root devices you must use a full (non-bundle) APK when patching. Refer to steps 3 and 4 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_3._downloading_the_yt_apk) to download and select the full APK from storage.




####**13. Nothing happens when I select the YT APK from storage**

Make sure you are using version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a version that is newer refer to step 1 of the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_1._downloading_the_revanced_manager_.26amp.3B_vanced_microg). If you already are using the correct version, continue with the following steps:

**a)** Uninstall the stock YouTube app. If your device doesn't allow you to uninstall it then go to the App info of stock YouTube > more info/options menu (as shown in [this image](https://imgur.com/a/0js3AZR)) > Uninstall updates.

**b)**  Install the YouTube APK that you downloaded while following step 3 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_3._downloading_the_yt_apk).

**c)** Open the ReVanced Manager > Patcher > Select an application > YouTube.

Continue from the middle of step 4 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_4._patching_the_apk).




####**14. "Error: Patch is not supported for this app version."**

Download an APK of the recommended/suggested version and patch that from storage. Refer to step 3 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_3._downloading_the_yt_apk).




####**15. Patcher is stuck on "Initializing..."**

The sources were not set properly. Refer to step 2 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._revanced_manager_settings).




####**16. Patcher is Aborting / Failing to apply patches**

If you see anywhere in the error "exit code = 135" or "exit code = 139" then follow the instructions in troubleshooting issue **#10**. If you don't see this error/exit code then continue with these 4 troubleshooting steps:

**a)** Make sure you are using version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a version that is newer refer to step 1 of the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_1._downloading_the_revanced_manager_.26amp.3B_vanced_microg).

**b)** If your device's language was set to a language that reads right-to-left when the failure occurred then set your device's language to English or any language that reads left-to-right. Then fully close the Manager, and try again.

**c)** Check what the recommended YouTube version is on [GitHub](https://github.com/inotia00/revanced-patches/tree/revanced-extended#readme) in case the manager was showing you the incorrect version. To check, press "Details" under the package name that you want to patch and look at the target version column. [Here is an image demonstration](https://imgur.com/a/qFHifJz). You must use a supported version.

* If it still doesn't work then patch on a different device or PC.

If you patch with the Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".

If you want to use a PC to patch then follow one of the PC methods in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#wiki).




####**17. "Error: Non-root install is not possible with the current patches selection."**

Patch again and include the `MicroG Support` patch.




####**18. "App not installed."**

**a)** If there was a google play protect pop-up when trying to install it then you must press **"More info"** and then tap the **"Install anyway"** button. If you press the "Got it" button it will not install. [Here](https://imgur.com/a/Ck8nfhn) is an image demonstrating this.

**b)** Ensure that you have enough free storage. YT ReVanced Extended may require more than 1 gigabyte to install without issue.

**c)** Uninstall the YT ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or Private Folder that your device features.




####**19. "App not installed as package conflicts with an existing package."**

**a)** Uninstall the YT ReVanced Extended app that is on your device before trying again. Make sure it is not installed in an alternate user profile or Private Folder that your device features.

**b)** Open the ReVanced Manager > Patcher > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Make sure the package name starts with "app.rvx" like in [this image](https://imgur.com/a/TUBgLLt). If it says something else, then you'll need to patch again, (using an unpatched APK,) and include the `MicroG Support` patch this time.

**c)** Create a detailed post if you are still having trouble.




####**20. "App not installed as package appears to be invalid."**

This error most often means that you are trying to install an app that is an older version than the already installed version. Android doesn't allow app downgrading. In the context of installing YT ReVanced Extended, here are some possible scenarios and solutions:

**a)** You are installing the unpatched YouTube APK that you downloaded from APKMirror.com. It is not necessary to install it. Refer to step 4 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_4._patching_the_apk) for info on selecting the YT APK from storage.

**b)** Your patched YT APK that you are installing was exported from the ReVanced Manager but does not have the `MicroG Support` patch applied to it. You can verify if this is the case by doing the following:

Open the ReVanced Manager > Patcher > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Check if the package name starts with "app.rvx" like in [this image](https://imgur.com/a/TUBgLLt). If it says something else, then you'll need to patch again, (using an unpatched APK,) and include the `MicroG Support` patch this time.

**c)** You are installing a patched YT ReVanced Extended APK that is an older version than the YT ReVanced Extended that is currently installed. Uninstall YT ReVanced Extended before installing the older version. Refer to the Exporting The Settings section in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_exporting_the_settings) for info on how to backup your settings from the installed YT ReVanced Extended so that you won't lose it all when you uninstall it.

**d)** You are installing an older version of Vanced MicroG than the one you already have installed. To uninstall the one you currently have installed, open your device Settings > Apps > Vanced MicroG > Uninstall.




####**21. App crashes on startup**

Common causes:

**a)** There was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#16** if this happened.

**b)** Make sure you selected the APK from storage and did not select the YouTube app, which can be an unsupported split-APK.