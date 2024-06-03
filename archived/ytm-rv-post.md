> (The markdown files of this guide and troubleshooting content can be found [here](https://github.com/KobeW50/ReVanced-Documentation/tree/main/my%20guides). Feel free to use them however you like :)

**BE SURE TO SEE MY [COMMENT]() WITH ALL OF THE TROUBLESHOOTING INFO.**




### **Before You Begin**

* If you are from Canada please read issue **#10** in my [comment below](https://www.reddit.com/r/revancedapp/comments/131beri/guide_for_installing_yt_music_revanced/jhzjzxo?) before you begin.

* This guide is for non-root installs.




### **Requirements**

* Patience and focus.

* A device running Android 8.0 or newer. 

* A device that isn't ARMv7 (aka armeabi-v7a). Patching errors may occur on ARMv7 devices. 




### **1. Downloading The Prerequisites**

**a)** Download and install the [latest ReVanced Manager](https://github.com/revanced/revanced-manager/releases/latest). (If you already have it installed, make sure it is the latest version.)

**b)** If you do not have GmsCore, download and install the [ReVanced GmsCore APK]().




### **2. Getting An Unpatched YT Music app/APK**

Install [YT Music from the Play Store](https://play.google.com/store/apps/details?id=com.google.android.apps.youtube.music). If it is already installed, make sure it is up-to-date.

(If you are patching to install the patched APK on a different device, **or** you cannot install from the Play Store, download one of the newer YTM APKs from [APKMirror.com](https://www.apkmirror.com/apk/google-inc/youtube-music/). Make sure to download the variant that matches the architecture of the device you plan to **install** the patched APK on, as demonstrated [here](https://imgur.com/a/NYoAUGS). You can find the supported architectures of your device by checking the bottom of the settings in the ReVanced Manager.)




### **3. Patching The APK**

**a)** If you have the YT Music app/APK that you are patching installed, open the ReVanced Manager > Patcher > Select an application > **YT Music**. 

**b)** If you don't have the app/APK installed, open the ReVanced Manager > Patcher > Select an application > **STORAGE**, and then select the YouTube Music APK that you just downloaded from APKmirror.

Now press "Select patches", and then the **Default** patches button, as shown in [this image](https://imgur.com/a/KzO4FlU). Do **NOT** add or remove patches unless you know what you are doing.

When you are done selecting the patches that you want, press "Done" and then press "Patch". It may take several minutes for the patches to apply. Do not exit the app. 


* **(Optional but recommended)** 

When it is finished patching you can save the APK as a file so that you have it for later use such as sharing it or to save you the trouble of needing to patch again if you get an installation error. To do this, tap the save icon as shown in [this image](https://imgur.com/a/FKD0okE). Then press "Save".




### **4. Installation**

Press "Install" and wait for it to finish installing. You may get a pop-up saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then press **"Install anyway"** as shown in [this image](https://imgur.com/a/iLP2m7l).

(If any issues arise check [this comment for troubleshooting info](https://www.reddit.com/r/revancedapp/comments/131beri/guide_for_installing_yt_music_revanced/jhzjzxo?).)




### **5. Additional Setup**

* **Open links by default**

Follow these steps so that when you open a YT Music link it will open in the YTM ReVanced app instead of the official YT Music app.

(If you are using MIUI, you'll need to use [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.)

**a)** Uninstall or disable the official YT Music app. Or go to the App info of official YT Music, Set as default / Open by default > Open supported links, Off.

**b)** Now open the App info of YTM ReVanced > Set as default / Open by default > Open supported links, On.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all On. (If you are on MIUI, tap on "Add link" and check off any URLs. Then press "Add".)

* **Android Auto Setup**

**Note:** From my experience and from what I heard, the YT Music ReVanced home screen will not load on Android Auto. But you can start a song, playlist, or album from the app on your phone and then control it from Android Auto.

Here's how to set it up:

**a)** You need to have included the `Bypass Certificate Checks` patch when you patched the app.

**b)** Once you have it installed with that patch, go to the Android Auto settings on your device.

**c)** Scroll down to "Version and permission info".

**d)** Tap on it 10 times to enter developer mode and then tap "OK" on the popup.

**e)** Tap the 3 dots in the upper-right corner of your screen and open the Developer settings.

**f)** Scroll down and make sure that Unknown sources are allowed.