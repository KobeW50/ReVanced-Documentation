## Last updated on July 6th, 2023

[.](https://imgur.com/a/1xqES5i)

**This guide will use a riskier patching method, which may fail to work properly when YouTube releases new YTM versions that can't be patched until the patches are updated to work on them. However, this issue is rare, and this patching method is simpler than the safer method. If you do not see a giant warning at the top of this post the method is probably in working order. The safer method is used in the [Wiki YTM guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/).**

.

## Things To Know

* This guide is for non-rooted devices.

* This guide will use the RVX Manager method. Check the [GitHub documentation](https://github.com/inotia00/revanced-documentation) for the other methods.
* Read the [Frequently Asked Questions](https://www.reddit.com/r/revancedextended/wiki/faq/).

## Requirements

‎

* Patience and focus. Follow the guide carefully.

* Your device must be running Android 8.0+.

* Your device must be non-rooted. If it is rooted, you will need to find a guide dedicated to rooted devices.

* Your device must be arm64-v8a. (More on that soon.)



## 1. Installing The Prerequisites

‎ **a)** If you do not have Vanced MicroG installed, download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). Or you can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest).

**b)** Download and install the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).



## 2. Checking Device Compatability

‎ Open the RVX Manager settings and scroll to the bottom and make sure it says **"Arch: arm64-v8a"** as shown in [this image](https://imgur.com/a/LcRUfwh). (If it does not say "arm64-v8a" you will need to use a different device to patch the APK. Please see the [YTM Troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/#wiki_issues_with_patching_.26amp.3B_installation) for more info.



## 3. Installing YT Music

Install [YT Music from the Play Store](https://play.google.com/store/apps/details?id=com.google.android.apps.youtube.music). If you already have it installed, make sure it is up-to-date.

(If you cannot install from the Play Store, download and install one of the newer YTM APKs from [APKMirror.com](https://www.apkmirror.com/apk/google-inc/youtube-music/). Make sure to install the arm64-v8a variant, as demonstrated [here](https://imgur.com/a/9QhPBBo).)



## 4. Patching

‎Open RVX Manager. Open the Patcher > Select an application > **YouTube Music**.

Now press "Select patches", and then select the patches that you want. I suggest using the Default patches to get the most features without breaking stuff.

You must **exclude** the `Custom Branding Music Name` patch.

The following 5 patches are the most important to include:

1\] **Music MicroG Support** (This patch is mandatory.)

2\] **Background Play** (Enables background playback. But cannot be disabled later.)

3\] **Certificate Spoof** (Adds support for Android Auto. Setup info at the end of the guide.)

4\] **Hide Music Ads** (Removes the video ads between songs.)

5\] **Spoof App Version** (Allows users to bypass the radio-only restriction that is in Canada and some other countries. Setup info at the end of the guide.)

You can select which custom branding icon you want to use, but make sure to only select one custom branding icon patch. You can view a preview of the 3 icons [here on Imgur](https://imgur.com/a/tjuLog1). **And remember to exclude the** `Custom Branding Music Name` **patch!**

When you are done selecting the patches that you want, press "Done" and then press "Patch". Patching generally takes 2-5 minutes. If you leave the app it may cancel without warning.

(Optional but recommended) When it is finished patching you can save the APK as a file so that you have it for later use, such as sharing it or to save you the trouble of needing to patch again if you get an installation error. To save the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".



## 5. Installation

When it is done patching press "Install" and wait for it to finish installing. You may get a message saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then press **"Install anyway"** as shown in [this image](https://imgur.com/a/bVN2kvd).



## 6. Additional Setup

(Default links, Android Auto, Canada playback fix, and Downloader setup.)




* **OPEN LINKS BY DEFAULT**

Follow these steps so that when you click a YouTube Music link it will open in the YTM Extended app instead of the official YouTube Music app.

(If you are using MIUI, you'll need to use the [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.)

**a)** Uninstall or disable the official YT Music app. Or go to the App info of official YT Music, Set as default / Open by default > Open supported links, **Off**.

**b)** Now open the App info of YTM Extended > Set as default / Open by default > Open supported links, **On**.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**. (If you are on MIUI, tap on "Add link" and check off any URLs. Then press "Add".)




* **ANDROID AUTO SETUP**

**Note:** From my experience and from what I heard, the YTM Extended home screen will not load on Android Auto. But you can start a song, playlist, or album from the app on your phone/tablet and you can then control it from Android Auto.

Here's how to set it up:

**a)** You need to have included the `Certificate Spoof` patch when you patched the app.

**b)** Once you have it installed with that patch, go to the Android Auto settings on your phone/tablet.

**c)** Scroll down to "Version and permission info".

**d)** Tap on it 10 times to enter developer mode and then tap "OK" on the popup.

**e)** Tap the 3 dots in the upper-right corner of your screen and open the Developer settings.

**f)** Scroll down and enable Unknown sources.




* **SPOOF APP VERSION SETUP (for Canadian users)**

**a)** You need to have included the `Spoof App Version` patch when you patched the app.

**b)** Open YTM Extended > Profile picture > Settings > ReVanced Extended > Spoof app version, on.

**c)** Fully close and restart the app.

If this does not work you can use an [old version of Vanced Music](https://www.apkmirror.com/apk/team-vanced/vanced-youtube-music/vanced-youtube-music-4-27-50-release/vanced-youtube-music-4-27-50-android-apk-download/) or use a VPN to a different country to get around the Radio-only restriction.




* **DOWNLOADER SETUP**

The download function in YTM Extended works by changing the Share button into a download button that calls upon the downloader of your choice to download the song. The default downloader is NewPipe, which you can download and install from [here](https://github.com/TeamNewPipe/NewPipe/releases/latest).

**Note:** At the time of this writing, there is a bug that makes it so that when you press the Share button for any song it will act as though you pressed the Share button for the currently playing song. Therefore you can only download the currently playing song.

Nevertheless, here is the setup:

**a)** You need to have included the `Share Button Hook` patch when you patched the app.

**b)** Open YTM Extended. Tap on the profile picture > Settings > ReVanced Extended > Hook share button, **On**.

**c)** Fully close and restart the app.

**d)** Open YTM Extended. Tap on the profile picture > Settings > ReVanced Extended > Hook type, **off**. It should now be set to open an external downloader.

**e)** Fully close the app.

Now when you press the Share button it will open a download prompt from NewPipe. If you want to use a different downloader you can check out [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq) for the download links and info of several downloaders. Keep in mind that PowerTube is no longer functioning for YT Music downloads.

After you installed the downloader that you like, open YTM Extended > Profile picture > Settings > ReVanced Extended > Package name of downloader. Then enter the package name of the downloader that you use. Make sure that there are no empty spaces. Then press "OK" and restart the app.




# More Info/Troubleshooting

Check the [YTM troubleshooting page](https://www.reddit.com/r/revancedextended/comments/13ipnn0/yt_music_revanced_extended_guide/jkb0e08) for troubleshooting help.

Check the [Wiki YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/) for the safer method and for comprehensive instructions.

Read the [Frequently Asked Questions](https://www.reddit.com/r/revancedextended/wiki/faq/) for the what, why, and how of ReVanced Extended.

Check out [inotia00's GitHub](https://github.com/inotia00).