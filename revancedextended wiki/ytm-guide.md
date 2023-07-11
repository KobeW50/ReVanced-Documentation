# **YT Music ReVanced Extended Guide**


### **Things To Know Before You Begin**

**a)** This guide is for patching and installing YT Music ReVanced Extended. (If you want to install YT ReVanced Extended, go to the [YT ReVanced Extended guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/).)

**b)** This guide will use the RVX Manager method. Check the [GitHub documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) for info on the other patching methods.

**c)** There is a [YTM troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/) which you should check if you get stuck at any point during this tutorial.




### **Requirements**

**a)** Your device must be running Android 8.0+.

**b)** Your device must be non-rooted. If it is rooted, look at the [GitHub documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) for a rooted guide.

**c)** Your device must use the arm64-v8a architecture. (If you aren't sure what yours is, you will be able to check shortly in the tutorial. If it is not arm64-v8a (ie: armeabi-v7a), refer to the [YTM troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/#wiki_issues_with_patching_.26amp.3B_installation) for instructions.)



### **1. Installing RVX Manager & Vanced MicroG**

**a)** If you do not have Vanced MicroG installed, download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). Or you can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest).

**b)** Download and install the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

(If you get an error saying "App not installed as app isn't compatible with your device." or "App not installed.", it likely means that your device is not supported by the RVX Manager. Refer to the [YTM troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/#wiki_issues_with_patching_.26amp.3B_installation) for further instructions.)




### **2. Getting An Unpatched YT Music**

Install [YT Music from the Play Store](https://play.google.com/store/apps/details?id=com.google.android.apps.youtube.music). If you already have it installed, make sure it is up-to-date.

(If you are patching to install the patched APK on a non-armv64-v8a device, download (but do not install) one of the newer YTM APKs from [APKMirror.com](https://www.apkmirror.com/apk/google-inc/youtube-music/). Make sure to download the variant that matches the architecture of the device you plan on installing the patched APK on, as demonstrated [here](https://imgur.com/a/NYoAUGS). If an Android device is not arm64-v8a it is almost certainly armeabi-v7a.)

(If you cannot install from the Play Store, download and install one of the newer YTM APKs from [APKMirror.com](https://www.apkmirror.com/apk/google-inc/youtube-music/). Make sure to install the arm64-v8a variant, as demonstrated [here](https://imgur.com/a/9QhPBBo).)




### **3. Patching YT Music**

Open the RVX Manager and press Patcher > Select an application > **YouTube Music**.

(If you are patching to install the patched APK on a non-armv64-v8a device, open the RVX Manager and press Patcher > Select an application > **Storage** > and then select the YTM APK file that you downloaded from APKMirror.)

Now press "Select patches", and then select the patches that you want. It is suggested to use the Default patches selection in order to get the most features without breaking stuff. To do so, press the "Default" button at the top of the patches selection screen.

If you decide not to use the default selection, keep the following things in mind:

**a)** You must **exclude** the `Custom Branding Music Name` patch.

**b)** You must **include the `Music MicroG Support` patch.

**c)** The 4 major patches are:

1] **Background Play** (Enables background playback.)

2] **Certificate Spoof** (Adds support for Android Auto. Additional setup info is in step 5 of the guide.)

3] **Hide Music Ads** (Removes the video ads between songs.)

4] **Spoof App Version** (Allows users to bypass the radio-only restriction that is in Canada and some other countries. Additional setup is in step 5 of the guide.)


You can select which custom branding icon you want to use, but make sure to only select one custom branding icon patch. You can view a preview of the 3 icons [here on Imgur](https://imgur.com/a/tjuLog1). **And remember to exclude the** `Custom Branding Music Name` **patch!**

When you are done selecting the patches that you want, press "Done" and then press "Patch". Patching generally takes 2-5 minutes. If you leave the app it may cancel without warning. Take screenshots of any errors / failures that occur to make troubleshooting easier.

* **Optional but recommended:**

When it is finished patching you can save the APK as a file so that you can send in to a different device or to save you the trouble of needing to patch again if you get an installation error. To save the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".




### **4. Installation**

Press "Install" and wait for it to finish installing. You may get a pop-up saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then press **"Install anyway"** as shown [here](https://imgur.com/a/iLP2m7l).

(If you get an "App not installed." error, tap the three dots in the upper right corner of the Manager screen and then press "Export APK", as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save". This will save you time when following the [YTM troubleshooting help](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/#wiki_issues_with_patching_.26amp.3B_installation).)




# **5. Additional Setup**

Aside from the detailed setup instructions below that are for the more complex configurations, many settings / patches can be enabled/disabled in the YTM Extended app. To find these settings, open the YTM Extended app > Profile picture > Settings > ReVanced Extended.




#### **Open Links By Default**

Follow these steps so that when you click a YouTube Music link it will open in the YTM Extended app instead of the official YouTube Music app.

(If you are using MIUI, you'll need to use the [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.)

**a)** Uninstall or disable the official YT Music app. Or go to the App info of official YT Music, Set as default / Open by default > Open supported links, **Off**.

**b)** Now open the App info of YTM Extended > Set as default / Open by default > Open supported links, **On**.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**. (If you are on MIUI, tap on "Add link" and check off any URLs. Then press "Add".)




#### **Android Auto Setup**

**Note:** From my experience and from what I heard, the YTM Extended home screen will not load on Android Auto. But you can start a song, playlist, or album from the app on your phone/tablet and you can then control it from Android Auto.

Here's how to set it up:

**a)** You need to have included the `Certificate Spoof` patch when you patched the app.

**b)** Once you have it installed with that patch, go to the Android Auto settings on your phone/tablet.

**c)** Scroll down to "Version and permission info".

**d)** Tap on it 10 times to enter developer mode and then tap "OK" on the popup.

**e)** Tap the 3 dots in the upper-right corner of your screen and open the Developer settings.

**f)** Scroll down and enable Unknown sources.




#### **Spoof App Version Setup (for Canadian users)**

**a)** You need to have included the `Spoof App Version` patch when you patched the app.

**b)** Open YTM Extended > Profile picture > Settings > ReVanced Extended > Spoof app version, on.

**c)** Fully close and restart the app.

If this does not work you can use an [old version of Vanced Music](https://www.apkmirror.com/apk/team-vanced/vanced-youtube-music/vanced-youtube-music-4-27-50-release/vanced-youtube-music-4-27-50-android-apk-download/) or use a VPN to a different country to get around the Radio-only restriction.




#### **Downloader Setup**

The download function in YTM Extended works by changing the Share button into a download button that calls upon the downloader of your choice to download the song. The default downloader is [Seal](https://github.com/JunkFood02/Seal/releases/latest).

**Note:** There is currently a bug that makes it so that when you press the Share button for any song it will act as though you pressed the Share button for the currently playing song. Therefore you can only download the currently playing song.

Nevertheless, here is the setup:

**a)** You need to have included the `Share Button Hook` patch when you patched the app.

**b)** Open YTM Extended. Tap on the profile picture > Settings > ReVanced Extended > Hook share button, **On**.

**c)** Fully close the app.

Now when you press the Share button it will try to open Seal to download the media. If you want to use a different downloader you can check out [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq) for the download links and info of several downloaders. (Keep in mind that PowerTube is no longer functioning for YT Music downloads.)

After you installed the downloader that you like, open YTM Extended > Profile picture > Settings > ReVanced Extended > Package name of downloader. Then enter the package name of the downloader that you use. Make sure that there are no empty spaces. Then press "OK" and restart the app.





# **Updating ReVanced Extended**

The RVX Manager does not yet feature an easy way to update existing ReVanced Extended apps that are on your device. For now, you must patch a new APK and then install the newly patched APK in place of the old ReVanced Extended app as an update. Installing it as an update will preserve your settings configuration.

Normally, you do not need to uninstall your old YTM Extended app before installing the new one. However, there are two exceptions.

**1)** Some bugs can persist if you do not do a fresh install.

**2)** If the new and old YTM Extended APKs were not signed using the same keystore file, the new YTM Extended APK will not be able to be installed without uninstalling the old YTM Extended app first.

Here are two common scenarios where the keystores wouldn't be the same:

**a)** You uninstalled the RVX Manager sometime after you patched your old YTM Extended APK. When you uninstalled the RVX Manager the keystore file was deleted. You then patched a new YTM Extended APK.

**b)** The new and old YTM Extended APKs were not patched on the same device. Every RVX Manager app uses a uniquely generated keystore file.




## **More Info/Troubleshooting**

Check the [YTM troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/) for troubleshooting help.

Read the [Frequently Asked Questions](https://www.reddit.com/r/revancedextended/wiki/faq/) for the what, why, and how of ReVanced Extended.

Check out [inotia00's GitHub](https://github.com/inotia00).