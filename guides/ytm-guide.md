#**YT Music ReVanced Extended Guide**


###**Things To Know Before You Begin**

**a)** This guide is for patching and installing YT Music ReVanced Extended. (If you want to install YT ReVanced Extended, go to the [YT ReVanced Extended guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/).)

**b)** This guide will use the ReVanced Manager method. Check the [GitHub documentation](https://github.com/inotia00/revanced-documentation) for info on the other patching methods.

**c)** There is a [YTM troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/) which you should check if you get stuck at any point during this tutorial.




###**Requirements**

**a)** Your device must be running Android 8.0+.

**b)** Your device must be non-rooted. If it is rooted, look at the [GitHub documentation](https://github.com/inotia00/revanced-documentation) for a rooted guide.

**c)** Your device must use the arm64-v8a (or x86 / x86_64) architecture. (If you aren't sure what yours is, you will be able to check it shortly in the tutorial. If it is not one of these (ie: armeabi-v7a), you can use still follow this guide to patch YTM Extended on a supported Android device and then export the patched APK to your non-supported device and install it. Alternatively, you can follow the [documentation](https://github.com/inotia00/revanced-documentation) to patch it using one of the other methods.)




###**1. Downloading The ReVanced Manager & Vanced MicroG**

**a)** If you do not have Vanced MicroG installed, download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). Or you can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest).

**b)** Download and install the version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a newer version already installed you must downgrade to the compatible version by following these steps:

1] Open the ReVanced Manager settings and export the keystore. Then save it. (If there is no keystore to export, ignore this step and step 4 below.)

2] Uninstall your current version of the Manager.

3] Install version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0).

4] Open the ReVanced Manager settings and import the keystore which you saved earlier. Do not change keystore password.




###**2. ReVanced Manager Settings**

We will now check to make sure that your device is supported. Open the ReVanced Manager settings and scroll to the bottom and make sure it says **"Arch: arm64-v8a"** or **"x86"** as shown in [this image](https://imgur.com/a/LcRUfwh). (If it does not say **"arm64-v8a"** or **"x86"**, you will need to use a different device to patch the APK. Please see the [YTM troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/#wiki_issues_with_patching_.26amp.3B_installation) for more info.)


Now scroll up to the Sources option in the Manager settings. Change the **Patches Organization** and the **Integrations Organization** to `inotia00` [as shown here](https://imgur.com/a/aLvOnhU). Do not leave any spaces at the end. Press "OK" and fully close the app.

(See the "Changing The Sources Back To The Official ReVanced Patches" section below if you need guidance to revert these changes later.)




###**3. Downloading The YTM APK**

After fully closing the ReVanced Manager, go to [this link on APKMirror.com](https://www.apkmirror.com/apk/google-inc/youtube-music/) and select the YouTube Music version that you would like to download.

(Do not use a version that is older than 5.21.52 or newer than 6.04.53. In general, it is suggested to download a version that was released prior to the most recent ReVanced Extended patch release, just in case there were any major changes to the newer YTM APKs that would cause the patches to fail since they weren't updated to support the newer, changed YTM APKs. You can check when the last ReVanced Extended patch release was by clicking [here](https://github.com/inotia00/revanced-patches/releases).)


Once you have decided on the version that want to use, download the variant of that version which supports the architecture of the device that you plan to **install** the patched APK on, as pointed out in [this image](https://imgur.com/a/fanr547).

Do not install the APK. Only download it.




###**4. Patching The APK**

Open the ReVanced Manager. Open the Patcher > Select an application > **STORAGE**, and then select the YouTube Music APK that you just downloaded from APKMirror. (It will probably be in your downloads folder.)

(The highlighted areas of [this image](https://imgur.com/a/WvLXio9) should now be identical to the corresponding areas on the Patcher screen of your device.)



Now press "Select patches", and then select the patches that you want. It is recommended that you use the default patches selection, which you can select by pressing the "Default" button at the top of the patches selection screen.



If you decide not to use the default selection, be sure to keep the following things in mind:

**a)** You must **exclude** the `Custom Branding Music Name` patch.

**b)** The following 5 patches are the most important to include:

1] **Music MicroG Support** (This patch is mandatory.)

2] **Background Play** (Enables background playback.)

3] **Certificate Spoof** (Adds support for Android Auto. Additional setup info is in step 6 of the guide.)

4] **Hide Music Ads** (Removes the video ads between songs.)

5] **Spoof App Version** (Allows users to bypass the radio-only restriction that is in Canada and some other countries. Additional setup info is in step 6 of the guide.)

**c)** You can also select which custom branding icon you want to use, but make sure to **only select one** custom branding icon patch. You can view a preview of the 5 icons [here on Imgur](https://imgur.com/a/QzXhuIp). But **remember to exclude** the `Custom Branding Music Name` patch.

(If you want to learn more about what each of the patches do, you can look at [this (unofficial) Google Doc](https://docs.google.com/document/d/1CTZBLYgVszL-P_qzvOIMuswG-3bxMBEqFblQBaRf8tQ/edit?usp=drivesdk) which has easy to understand descriptions and screenshot demonstrations. Huge thanks to u/hlytus and u/SpacellaryUS!)

When you are done selecting the patches that you want, press "Done" and then press "Patch". It may take several minutes for the patches to apply. Do not exit the app. Take screenshots of any failures in case you need help later.

* **Optional but recommended:**

When it is finished patching you can save the APK as a file so that you have it for later use, such as sharing it or to save you the trouble of needing to patch again if you get an installation error. To save the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".




###**5. Installation**

When it is done patching press "Install" and wait for it to finish installing. You may get a message saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then press **"Install anyway"** as shown in [this image](https://imgur.com/a/iLP2m7l).

(If you get an "App not installed." error, tap the three dots in the upper right corner of the Manager screen and then press "Export APK", as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save". This will save you time when following the [YTM troubleshooting help](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/#wiki_issues_with_patching_.26amp.3B_installation).)




#**6. Additional Setup**


Aside from the detailed setup instructions below for the more complex configurations, some settings and patches can be enabled/disabled in the YTM Extended app. To find these settings, open the YTM Extended app > Profile picture > Settings > ReVanced Extended.




####**Open Links By Default**

Follow these steps so that when you click a YouTube Music link it will open in the YTM Extended app instead of the official YouTube Music app.

(If you are using MIUI, you'll need to use the [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.)

**a)** Uninstall or disable the official YT Music app. Or go to the App info of official YT Music, Set as default / Open by default > Open supported links, **Off**.

**b)** Now open the App info of YTM Extended > Set as default / Open by default > Open supported links, **On**.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**. (If you are on MIUI, tap on "Add link" and check off any URLs. Then press "Add".)




####**Android Auto Setup**

**Note:** From my experience and from what I heard, the YTM Extended home screen will not load on Android Auto. But you can start a song, playlist, or album from the app on your phone/tablet and you can then control it from Android Auto.

Here's how to set it up:

**a)** You need to have included the `Certificate Spoof` patch when you patched the app.

**b)** Once you have it installed with that patch, go to the Android Auto settings on your phone/tablet.

**c)** Scroll down to "Version and permission info".

**d)** Tap on it 10 times to enter developer mode and then tap "OK" on the popup.

**e)** Tap the 3 dots in the upper-right corner of your screen and open the Developer settings.

**f)** Scroll down and enable Unknown sources.




####**Spoof App Version Setup (for Canadian users)**

**a)** You need to have included the `Spoof App Version` patch when you patched the app.

**b)** Open YTM Extended > Profile picture > Settings > ReVanced Extended > Spoof app version, on.

**c)** Fully close and restart the app.

If this does not work you can use an [old version of Vanced Music](https://www.apkmirror.com/apk/team-vanced/vanced-youtube-music/vanced-youtube-music-4-27-50-release/vanced-youtube-music-4-27-50-android-apk-download/) or use a VPN to a different country to get around the Radio-only restriction.




####**Downloader Setup**

The download function in YTM Extended works by changing the Share button into a download button that calls upon the downloader of your choice to download the song. The default downloader is NewPipe, which you can download and install from [here](https://github.com/TeamNewPipe/NewPipe/releases/latest).

**Note:** As of patches version 2.173.10, there is a bug that makes it so that when you press the Share button for any song it will act as though you pressed the Share button for the currently playing song. Therefore you can only download the currently playing song.

Nevertheless, here is the setup:

**a)** You need to have included the `Share Button Hook` patch when you patched the app.

**b)** Open YTM Extended. Tap on the profile picture > Settings > ReVanced Extended > Hook share button, **On**.

**c)** Fully close and restart the app.

**d)** Open YTM Extended. Tap on the profile picture > Settings > ReVanced Extended > Hook type, **off**. It should now be set to open an external downloader.

**e)** Fully close the app.

Now when you press the Share button it will open a download prompt from NewPipe. If you want to use a different downloader you can check out [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq) for the download links and info of several downloaders. Keep in mind that PowerTube is no longer functioning for YT Music downloads.

After you installed the downloader that you like, open YTM Extended > Profile picture > Settings > ReVanced Extended > Package name of downloader. Then enter the package name of the downloader that you use. Make sure that there are no empty spaces. Then press "OK" and restart the app.




#**Changing The Sources Back To The Official ReVanced Patches**

If you would like to go back and have the regular ReVanced patches instead of the ReVanced Extended (inotia00) patches in the ReVanced Manager, follow these steps:

Open the ReVanced Manager. Go to the settings and open the Sources menu.

In some versions of the Manager, you can use the reset button, on the top-right of the sources menu. Press it, confirm, and then fully close the app.

To do it manually, change the **Patches Organization** and the **Integrations Organization** to `revanced` as shown [here](https://imgur.com/a/yIwMq41). Do not leave any spaces at the end. Press "OK" and fully close the app.




#**Updating ReVanced Extended**

The ReVanced Manager does not yet feature an easy way to update existing ReVanced Extended apps that are on your device. For now, you must patch a new APK and then install the new APK in place of the old APK as an update. Installing it as an update will preserve your settings configuration.

Normally, you do not need to uninstall your old YTM Extended app before installing the new one. However, there are two exceptions.

**1)** Some bugs can persist if you do not do a fresh install.

**2)** If the new and old YTM Extended APKs were not signed using the same keystore file, the new YTM Extended APK will not be able to be installed without uninstalling the old YTM Extended app first.

Here is an oversimplification of two common scenarios where the keystores wouldn't be the same:

**a)** You uninstalled the ReVanced Manager sometime after you patched your old YTM Extended APK. When you uninstalled the ReVanced Manager the keystore file was deleted. You then patched a new YTM Extended APK.

**b)** The new and old YTM Extended APKs were not patched on the same device. Every ReVanced Manager app uses a uniquely generated keystore file.

In general, if you don't delete stuff and you patch your APKs using the same ReVanced Manager on the same device the keystore files will stay intact.




## **More Info/Troubleshooting**

Check the [YTM troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/) for troubleshooting help.

Read the [Frequently Asked Questions](https://www.reddit.com/r/revancedextended/wiki/faq/) for the what, why, and how of ReVanced Extended.

Check out [inotia00's GitHub](https://github.com/inotia00).