#**YT ReVanced Extended Guide**

#**For Experienced ReVanced Manager Users**

If you are already experienced with the ReVanced Manager and you understand the principles of it, then you only need to learn one additional step for you to patch ReVanced Extended. But first, here are some important things to know:

**a)** ReVanced Extended will install as a separate app from YouTube ReVanced.

**b)** If you use a method other than the ReVanced Manager to patch, or if your device is rooted, look at the [GitHub documentation](https://github.com/inotia00/revanced-documentation) for more ReVanced Extended guides.

**c)** If you are using the ReVanced Manager to patch you must use version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a newer version already installed you must downgrade to the compatible version by following these steps:

1] Open the ReVanced Manager settings and export the keystore. Then save it. (If there is no keystore to export, ignore this step and step 4 below.)

2] Uninstall your current version of the Manager.

3] Install version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0).

4] Open the ReVanced Manager settings and import the keystore which you saved earlier. Do not change the keystore password.



####**Changing The Sources**


Open the ReVanced Manager Settings > Sources, and change the **Patches organization** and the **Integrations organization** to `inotia00`. Make sure you did not leave any spaces at the end. It should look like [this](https://imgur.com/a/aLvOnhU). Press "OK" and fully close the app.

Then follow the same steps you would take to patch official YouTube ReVanced. Keep in mind that the recommended/suggested version of ReVanced Extended is likely different than the official ReVanced so make sure to check the recommended version for ReVanced Extended in the Manager or [here in the GitHub](https://github.com/inotia00/revanced-patches/tree/revanced-extended#readme). (If you are checking what the recommended version is on GitHub, press "Details" underneath "com.google.android.youtube" and look at the target version column. [Here is an image demonstration](https://imgur.com/a/qFHifJz).)



**Changing Back The Sources To Get The Official ReVanced Patches**

If you would like to go back and have the regular ReVanced patches instead of the ReVanced Extended (inotia00) patches in the ReVanced Manager, follow these steps:

Open the ReVanced Manager. Go to the settings and open the Sources menu.

In some versions of the Manager, you can use the reset button, on the top-right of the sources menu. Press it, confirm, and then fully close the app.

To do it manually, change the **Patches Organization** and the **Integrations Organization** to `revanced` as shown [here](https://imgur.com/a/yIwMq41). Do not leave any spaces at the end. Press "OK" and fully close the app.






#**For Inexperienced Users**


###**Things To Know Before You Begin**

**a)** Check out the [Frequently Asked Questions](https://www.reddit.com/r/revancedextended/wiki/faq/).

**b)** This guide is for patching and installing YouTube ReVanced Extended. (If you want to install YT Music ReVanced Extended, go to the [YTM Extended guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/).)

**c)** This guide will use the ReVanced Manager method. Refer to the [GitHub documentation](https://github.com/inotia00/revanced-documentation) for info on the other patching methods.

**d)** There is a [YT troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/yt-troubleshooting/) which you should check if you get stuck at any point during this tutorial.





###**Requirements**

**a)** Your device must be running Android 8.0+.

**b)** Your device must be non-rooted. If it is rooted, look at the [GitHub documentation](https://github.com/inotia00/revanced-documentation) for a rooted guide.

**c)** Your device must use the arm64-v8a (or x86 / x86_64) architecture. (If you aren't sure what yours is, you will be able to check it shortly in the tutorial. If it is not one of these (ie: armeabi-v7a), you can use still follow this guide to patch YT ReVanced Extended on a supported Android device and then export the patched APK to your non-supported device and install it. Alternatively, you can follow the [documentation](https://github.com/inotia00/revanced-documentation) to patch it using one of the other methods.)




###**1. Downloading The ReVanced Manager & Vanced MicroG**

**a)** If you do not have Vanced MicroG installed, download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). Or you can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest).

**b)** Download and install the version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0). If you have a newer version already installed you must downgrade to the compatible version by following these steps:

1] Open the ReVanced Manager settings and export the keystore. Then save it. (If there is no keystore to export, ignore this step and step 4 below.)

2] Uninstall your current version of the Manager.

3] Install version **1.2.0** of the [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/tag/v1.2.0).

4] Open the ReVanced Manager settings and import the keystore which you saved earlier. Do not change keystore password.




###**2. ReVanced Manager Settings**

We will now check to make sure that your device is supported, and then set the ReVanced Manager to use the ReVanced Extended patches.

Open the ReVanced Manager settings and scroll to the bottom and make sure it says **"Arch: arm64-v8a"** or **"x86"** as shown in [this image](https://imgur.com/a/LcRUfwh). (If it does not say **"arm64-v8a"** or **"x86"**, you will need to use a different device to patch the APK. Please see the [YT troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/yt-troubleshooting/#wiki_issues_with_patching_.26amp.3B_installation) for more info.)


Now scroll up to the Sources option in the Manager settings. Change the **Patches Organization** and the **Integrations Organization** to `inotia00` [as shown here](https://imgur.com/a/aLvOnhU). Do not leave any spaces at the end. Press "OK" and fully close the app.


(See the "Changing The Sources Back To The Official ReVanced Patches" section below if you need guidance to revert these changes later.)





###**3. Downloading The YT APK**

We will now check which version of YouTube we will need to download for us to patch it. If you have stock YouTube installed, reboot the ReVanced Manager and press Patcher > Select an application. It will say the currently suggested version in the YouTube box, as shown [here](https://imgur.com/a/IzqCViD).

You can also check the recommended version [here in the GitHub](https://github.com/inotia00/revanced-patches/tree/revanced-extended#readme). (Press **"Details"** underneath **"com.google.android.youtube"** and look at the target version column. [Here is an image demonstration](https://imgur.com/a/qFHifJz).)

Keep in mind that the recommended version is constantly changing so the version it shows for you will almost certainly be different than the one shown in these images. Also, the suggested version for YT ReVanced Extended is usually not the same as the version suggested for official YT ReVanced.

Head to [this link on APKMirror.com](https://www.apkmirror.com/apk/google-inc/youtube/) and find the YouTube APK for the recommended/suggested version.

(If you are unable to find the recommended version it may be because it hasn't yet been released on apkmirror.com. You can either wait for it to release or check the previously recommended version on [GitHub](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-json-format) and use one of them.)

After you have found the recommended version, download the `nodpi` variant of that APK. Here are some screenshots to demonstrate that.

[Find the APK for the recommended version.](https://imgur.com/a/x8UwR5S)

[Select the `nodpi` version to download.](https://imgur.com/a/cK3yhZV)

[Press the big red "Download APK" button.](https://imgur.com/a/VOulscb)

Do not install the YT APK when it has finished downloading.





###**4. Patching The APK**

Open the ReVanced Manager. Open the Patcher > Select an application > **STORAGE**, and then select the YouTube APK that you just downloaded from APKMirror. (It will probably be in your downloads folder.)

Now press "Select patches", and then select the patches that you want. It is recommended that you use the default patches selection, which you can select by pressing the "Default" button at the top of the patches selection screen.


If you decide not to use the default selection, be sure to keep the following things in mind:

**a)** You **must** include the `MicroG Support` patch. It is also **strongly** recommended that you include the `Protobuf Spoof` patch.

**b)** You can also select which custom branding icon you want to use, but make sure to **only select one** custom branding icon patch. You can view a preview of the 5 icons [here on Imgur](https://imgur.com/a/neHJcDt).

**c)** Make sure to look through all of the patches so you don't accidentally exclude any features.

(If you want to learn more about what each of the patches do, you can look at [this (unofficial) Google Doc](https://docs.google.com/document/d/1CTZBLYgVszL-P_qzvOIMuswG-3bxMBEqFblQBaRf8tQ/edit?usp=drivesdk) which has easy to understand descriptions and screenshot demonstrations. Huge thanks to u/hlytus and u/SpacellaryUS!)

When you are done selecting the patches that you want, press "Done" and then press "Patch".

Wait for the patching to be complete, and take screenshots of any errors/failures in case you need help later. Patching generally takes 2-15 minutes. If you leave the app it may cancel without warning.


* **Optional but recommended:**

When it is finished patching you can save the APK as a file so that you have it for later use, such as sharing it or to save you the trouble of needing to patch again if you get an installation error. To save the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".





###**5. Installation**

Press "Install" and wait for it to finish installing. You may get a message saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then **"Install anyway"** as shown [here](https://imgur.com/a/iLP2m7l).

(If you get an "App not installed." error, tap the three dots in the upper right corner of the Manager screen and then press "Export APK", as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save". This will save you time when following the [YT troubleshooting help](https://www.reddit.com/r/revancedextended/wiki/yt-troubleshooting/#wiki_issues_with_patching_.26amp.3B_installation).)





#**6. Additional Setup**

Aside from the detailed setup instructions below for the more complex configurations, many settings and patches can be enabled/disabled in the YT ReVanced Extended app. If there is something that is hidden that you want to unhide, or if there is something extra that you want to remove, you can most likely change it in one of these settings menus.

To find the ReVanced Extended settings, open the YT ReVanced Extended app > Profile picture > Settings > ReVanced Extended.

To find the SponsorBlock settings: Profile picture > Settings > SponsorBlock.

To find the  Return YouTube Dislike settings: Profile picture > Settings > Return YouTube Dislike.





####**Open Links By Default**

Follow these steps so that when you click a YouTube link it will open in the YT Extended app instead of the official YouTube app.

(If you are using MIUI, you'll need to use the [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.)

**a)** Uninstall or disable the official YouTube app. Or go to the App info of official YouTube, tap on Set as default / Open by default > Open supported links, **Off**.

**b)** Now open the App info of YT ReVanced Extended > Set as default / Open by default > Open supported links, **On**.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**. (If you are on MIUI, tap on "Add link" and check off all URLs. Then press "Add".)




####**Downloader Setup**

There are three important things to know about downloading in YT ReVanced Extended.

**a)** You need to have included the `Overlay Buttons` patch.

**b)** The ReVanced Extended download function is completely separate from the built-in download button which is reserved for YT Premium members. The ReVanced Extended download button can be enabled by going into Settings > ReVanced Extended > Overlay buttons > Show download button, **On**. The download button will appear beside the full-screen button in the video player.

**c)** To download videos you need a 3rd party downloader app installed on your device, such as PowerTube, Seal, or NewPipe. To install a downloader, open up YT ReVanced Extended and navigate to Settings > ReVanced Extended > Overlay buttons > Downloader settings. Now select the downloader that you want to use and then press "Install". It will direct you to the GitHub page, where you can download and install the downloader.

After it is installed and working, open up YT ReVanced Extended again and navigate to Settings > ReVanced Extended > Overlay buttons > Downloader settings, and select the downloader that you installed. Press "Save". Now when you press the download button it will open a pop-up from the downloader so that you can quickly and easily download videos.




#**Changing The Sources Back To The Official ReVanced Patches**

If you would like to go back and have the regular ReVanced patches instead of the ReVanced Extended (inotia00) patches in the ReVanced Manager, follow these steps:

Open the ReVanced Manager. Go to the settings and open the Sources menu.

In some versions of the Manager, you can use the reset button, on the top-right of the sources menu. Press it, confirm, and then fully close the app.

To do it manually, change the **Patches Organization** and the **Integrations Organization** to `revanced` as shown [here](https://imgur.com/a/yIwMq41). Do not leave any spaces at the end. Press "OK" and fully close the app.




#**Updating ReVanced Extended**

The ReVanced Manager does not yet feature an easy way to update existing ReVanced Extended apps that are on your device. For now, you must patch a new APK and then install the new APK in place of the old APK as an update. Installing it as an update will preserve your settings configuration.

Normally, you do not need to uninstall your old YT ReVanced Extended app before installing the new one. However, there are two exceptions.

**1)** Some bugs can persist if you do not do a fresh install.

**2)** If the new and old YT ReVanced Extended APKs were not signed using the same keystore file, the new YT ReVanced Extended APK will not be able to be installed without uninstalling the old YT ReVanced Extended app first.

Here is an oversimplification of two common scenarios where the keystores wouldn't be the same:

**a)** You uninstalled the ReVanced Manager sometime after you patched your old YT ReVanced Extended APK. When you uninstalled the ReVanced Manager the keystore file was deleted. You then patched a new YT ReVanced Extended APK.

**b)** The new and old YT ReVanced Extended APKs were not patched on the same device. Every ReVanced Manager app uses a uniquely generated keystore file.

In general, if you don't delete stuff and you patch your APKs using the same ReVanced Manager on the same device the keystore files will stay intact.



####**Exporting The Settings**

If you need or want to uninstall the old YT ReVanced Extended APK and install the new APK as a fresh install, you can still export the settings from the old YT ReVanced Extended app and then import that file into the new app so that you won't need to reconfigure all of your settings.

To do this, open the old YT ReVanced Extended app and tap on the profile picture > Settings > ReVanced Extended > Miscellaneous > Import/Export settings > Export settings > Save.

You'll probably also want to export the SponsorBlock settings as well. Tap on the profile picture > Settings > SponsorBlock > Import/Export settings. Now copy all of the text and save it until you are ready to paste it into the new YT ReVanced Extended app.

You can now uninstall the old YT ReVanced Extended app.

After installing the new YT ReVanced Extended app, open it and tap on the profile picture > Settings > ReVanced Extended > Miscellaneous > Import/Export settings > Import settings. Now select the settings file that you exported from the old app.

Now for the SponsorBlock settings. Tap on the profile picture > Settings > SponsorBlock > Import/Export settings. Now remove all of the text and paste in the text that you copied from the SponsorBlock settings in the old app.

The built-in YouTube settings will still need to be configured, as well as any settings for features that your old app didn't have.




## **More Info/Troubleshooting**

Check the [YT troubleshooting page](https://www.reddit.com/r/revancedextended/wiki/yt-troubleshooting/) for troubleshooting help.

Read the [Frequently Asked Questions](https://www.reddit.com/r/revancedextended/wiki/faq/) for the what, why, and how of ReVanced Extended.

Check out [inotia00's GitHub](https://github.com/inotia00).