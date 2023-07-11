# **YT ReVanced Extended Troubleshooting**

(For troubleshooting help related to YT **Music** Extended click [here](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/).)



# **Issues Within YT ReVanced Extended**

(See below for patching and installation troubleshooting.)



#### **1. No internet connection / The home page isn't loading**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




#### **2. I'm having issues signing in to my Google account**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




#### **3. "com.deniscerri.ytdl is not installed."**

Refer to step 5 of the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_downloader_setup) to understand and set up the download function in YT ReVanced Extended.




#### **4. Videos stop and buffer infinitely**

Make sure you YT ReVanced Extended is up-to-date.

If buffering persists open YT ReVanced Extended, tap the profile picture > Settings > ReVanced Extended > Miscellaneous > Spoof player parameter, ON. Restart the app.

Then go to Settings > ReVanced Extended > Miscellaneous > Spoof player parameter type, ON.




#### **5. YouTube Shorts and/or the Shorts button is/are gone**

**To unhide Shorts in feeds:**

Go to Settings > ReVanced Extended > Shorts > Hide shorts shelf, **Off**.

**To unhide the Shorts button:**

Go to Settings > ReVanced Extended > Navigation > Hide shorts button, **Off**.




#### **6. The player UI doesn't go away**

**a)** Make sure you don't have it set to never go away in the Accessibility settings. To check, navigate to Settings > Accessibility. Either disable accessibility settings or lower the timer so that it goes away sooner.

**b)** If that wasn't the issue, simply close and restart the app.




#### **7. SponsorBlock is not working**

This likely means that the SponsorBlock servers are down. You can check the server status [here](https://status.sponsor.ajay.app/).




#### **8. Watch history isn't being saved on YouTube**

Whitelist `s.youtube.com` in your ad-blocker.







# **Issues With Patching & Installation**


#### **9. My device is not supported**

You'll need to patch on a different Android device or on PC.

If you patch with the RVX Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




#### **10. "Feature not implemented: This application is a split APK and cannot be selected."**

On non-root devices you must use a full (non-bundle) APK when patching. Refer to steps 2 and 3 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._downloading_the_yt_apk) to download and select the full APK from storage.




#### **11. Nothing happens when I select the YT APK from storage**

Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest). If you already are using the correct version, continue with the following steps:

**a)** Uninstall the stock YouTube app. If your device doesn't allow you to uninstall it then go to the App info of stock YouTube > more info / options menu (as shown in [this image](https://imgur.com/a/0js3AZR)) > Uninstall updates.

**b)**  Install the YouTube APK that you downloaded while following step 2 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._downloading_the_yt_apk).

**c)** Open the RVX Manager > Patcher > Select an application > YouTube.

Continue from the middle of step 3 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_3._patching_the_apk).




#### **12. "Error: Patch is not supported for this app version."**

Download an APK of the recommended/suggepd version and patch that from storage. Refer to step 2 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._downloading_the_yt_apk).




#### **13. Patcher is Aborting / Failing to apply patches**

**a)** Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

**b)** If your device's language was set to a language that reads right-to-left when the failure occurred then set your device's language to English or any language that reads left-to-right. Then fully close the Manager, and try again.

* If it still doesn't work then create a post with a screenshot or logs of the error. Alternatively, you can patch on a different device or use a different patching method.

If you patch with the RVX Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




#### **14. "Error: Non-root install is not possible with the current patches selection."**

Patch again and include the `MicroG Support` patch.




#### **15. "App not installed."**

**a)** If there was a google play protect pop-up when trying to install it then you must press **"More details"** and then tap the **"Install anyway"** button. If you press the "Got it" button it will not install. [Here](https://imgur.com/a/Ck8nfhn) is an image demonstrating this.

**b)** Ensure that you have enough free storage. Depending on the device, it may require more than 1.5 gigabytes to install without issue.

**c)** Uninstall the YT ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.




#### **16. "App not installed as package conflicts with an existing package."**

**a)** Uninstall the YT ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.

**b)** Open the RVX Manager > Patcher > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Make sure the package name starts with "app.rvx" like in [this image](https://imgur.com/a/TUBgLLt). If it says something else, then you'll need to patch again, (using an unpatched APK of the suggested version,) and include the `MicroG Support` patch this time.

**c)** Create a detailed post if you are still having trouble.




#### **17. "App not installed as package appears to be invalid."**

This error most often means that you are trying to install an app that is an older version than the already installed version. Android doesn't allow app downgrading. In the context of installing YT ReVanced Extended, here are some possible scenarios and solutions:

**a)** You are installing the unpatched YouTube APK that you downloaded from APKMirror.com. It is not necessary to install it. Refer to step 3 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_3._patching_the_apk) for info on selecting the YT APK from storage.

**b)** Your patched YT APK that you are installing was exported from the RVX Manager but does not have the `MicroG Support` patch applied to it. You can verify if this is the case by doing the following:

Open the RVX Manager > Patcher > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Check if the package name starts with "app.rvx" like in [this image](https://imgur.com/a/TUBgLLt). If it says something else, then you'll need to patch again, (using an unpatched APK of the suggested version,) and include the `MicroG Support` patch this time.

**c)** You are installing a patched YT ReVanced Extended APK that is an older version than the YT ReVanced Extended that is currently installed. Uninstall YT ReVanced Extended before installing the older version. Refer to the Exporting The Settings section in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_exporting_the_settings) for info on how to backup your settings from the installed YT ReVanced Extended so that you won't lose it all when you uninstall it.

**d)** You are installing an older version of Vanced MicroG than the one you already have installed. To uninstall the one you currently have installed, open your device Settings > Apps > Vanced MicroG > Uninstall.




#### **18. App crashes on startup**

Common causes:

**a)** There was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#13** if this happened.

**b)** Make sure you selected the APK from storage and did not select the YouTube app, which can be an unsupported split-APK.