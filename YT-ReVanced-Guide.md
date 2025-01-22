Last updated: Jan 19, 2025


### **Before You Begin**

- You will need a device running Android 8 or newer

- This guide is for non-root installations




### **1. Getting the APKs**

**1.1)** Download and install [ReVanced Manager](https://revanced.app/download). (If you already have it installed, make sure it is the latest version.)

**1.2)** Download, but do **NOT** install this [YouTube 19.47.53 APK](https://www.apkmirror.com/apk/google-inc/youtube/youtube-19-47-53-release/youtube-19-47-53-android-apk-download/). (This is the currently suggested YouTube APK for patching.)

> For a more robust method of downloading the YouTube APK, see the footnotes.[^1]




### **2. Patching**

**2.1)** Open ReVanced Manager. If prompted, grant ReVanced Manager permission to install unknown apps.

**2.2)** Go to the ReVanced Manager settings and disable `Save patched app`. (This prevents a bug.)

**2.3)** Go to the Patcher tab and press Select an app. Then, press **Storage**

<img src="https://github.com/KobeW50/ReVanced-Documentation/blob/main/images/yt-revanced-guide/select-from-storage.png" alt="select-from-storage" width="280"/>

**2.4)** Select the YouTube APK you just downloaded. (It will likely be in your Downloads folder.)

**2.5)** ReVanced Manager should now show the YouTube app selected, with several dozen selected patches. Press the Patch button to begin patching.

> If you want to customize the patch selection, see the footnotes.[^2]

**2.6)** Keep ReVanced Manager open while the app is being patched. Make sure no errors occur. (The patch log should be easily readable.)




### **3. Installing YouTube ReVanced and GmsCore**

**3.1)** When patching completes press Install. 

> [!TIP]
> You can also export the patched APK file using the button on the bottom left.
>
> <img src="https://github.com/KobeW50/ReVanced-Documentation/blob/main/images/yt-revanced-guide/export-apk.png" alt="are-you-a-developer-create-an-app" width="280"/>

> [!NOTE]
> If there is a popup saying that the installation was blocked because it is an unknown app, press "**More details**" and then "**Install anyway**".
>
> <img src="https://github.com/KobeW50/ReVanced-Documentation/blob/main/images/yt-revanced-guide/install-anyway_old.jpeg" alt="install-anyway" width="280"/>

**3.2)** If ReVanced GmsCore is not installed, you will need to install it in order for YouTube ReVanced to run in a non-root environment. If it's not installed, the [download page](https://github.com/ReVanced/GmsCore/releases/latest) will automatically open when you try opening YouTube ReVanced. If you are using a Huawei device, be sure to install the special version for your device.

You are now done! Note that there is a section in the YouTube ReVanced settings for configuring the ReVanced features. Also, see [this page](https://github.com/KobeW50/ReVanced-Documentation/blob/main/reddit_posts/YT-ReVanced-Guide-comment.md) for info on making YouTube links open in YouTube ReVanced and setting up the external download feature.



___
### **How do I update YouTube ReVanced?**

To update, you will need to download the suggested YouTube APK, patch it, and install it. Of course, make sure your ReVanced Manager is up-to-date. There is no reason to uninstall your current YouTube ReVanced or ReVanced Manager when updating.

___
[^1]: Instead of relying on this guide (which is manually updated) to get a YouTube APK, it's best to use the YouTube version suggested in ReVanced Manager, as shown in [this image](https://raw.githubusercontent.com/KobeW50/ReVanced-Documentation/refs/heads/main/images/yt-revanced-guide/suggested-version.png). Tap on the suggested version in ReVanced Manager to open a search for that YouTube APK. Find and open the result from apkmirror.com with the suggested version. You'll need to make sure that you download the `nodpi` variant of the suggested YouTube version rather than the bundle variant, as shown in [this image](https://raw.githubusercontent.com/KobeW50/ReVanced-Documentation/refs/heads/main/images/yt-revanced-guide/apkmirror-youtube.png).

[^2]: To change the patch selection, enable the `Allow changing patch selection` option in the ReVanced Manager settings. Then, after selecting the YouTube APK from storage, press the Selected patches and configure the patches and patch options to your liking. If you don't understand what something does it's best not to tinker with it.
