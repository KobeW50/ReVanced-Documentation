Last updated: Oct 24, 2025


### Before You Begin

- You will need a device running Android 8 or newer

- This guide is for non-root installations




### 1. Preparing for Patching

**1.1)** Download and install [ReVanced Manager](https://revanced.app/download). (If you already have it installed, make sure it is the latest version.)

**1.2)** Download and install the APKMirror downloader APK from [here](https://github.com/ReVanced/revanced-manager-downloaders/releases/latest). (It is a plugin for ReVanced Manager.)

> [!TIP]
> While it won't be used in this guide, you may want to also download and install the Play Store downloader APK to help with patching some apps other than YouTube.

**1.3)** Open ReVanced Manager. If prompted, grant ReVanced Manager permission to install unknown apps and to run in the background.

**1.4)** Follow the prompt to configure the downloader plugins (or go to Settings > Downloads). Grant trust to the downloader plugin(s).




### 2. Patching

**2.1)** Return to the Apps tab and press the `+` button.

<img src="/images/yt-revanced-guide/add-an-app.jpg" width="270"/>

**2.2)** Wait for the app list to load and then select YouTube.

> [!NOTE]
> If you don't see YouTube, search for `com.google.android.youtube` and select it.

**2.3)** Press the `Patch` button.

> If you want to customize the patch selection, see the footnotes.[^1]

**2.4)** Follow the prompt to open APKMirror. Then, navigate APKMirror to download the non-bundle variant of the YouTube APK. Below is a video walkthrough.

<img src="/images/yt-revanced-guide/apkmirror-walkthrough.jpg" width="296"/>

**2.5)** Patching will proceed once the APK is downloaded. Keep ReVanced Manager open while YouTube is being patched. Make sure no errors occur.




### 3. Installing YouTube ReVanced and GmsCore

**3.1)** When patching completes press `Install`. 

> [!NOTE]
> If there is a popup saying that the installation was blocked because it is an unknown app, press "**More details**" and then "**Install anyway**".

> [!TIP]
> You can also export the patched APK file using the save button on the bottom left.

**3.2)** If ReVanced GmsCore is not installed, you will need to install it in order for YouTube ReVanced to run in a non-root environment. If it's not installed, the [download page](https://github.com/ReVanced/GmsCore/releases/latest) will automatically open when you try opening YouTube ReVanced. If you are using a Huawei device, be sure to install the special version for your device.

You are now done! Note that there is a section in the YouTube ReVanced settings for configuring the added features. Read on for info about updating YouTube ReVanced, making YouTube links open in YouTube ReVanced, and setting up the external download feature.



___

### How do I update YouTube ReVanced?

To update, you will need to patch and install YouTube again just like in the [patching section](#2-Patching) of this guide. Of course, make sure your ReVanced Manager is up-to-date. There is no reason to uninstall your current YouTube ReVanced or ReVanced Manager when updating.



### How do I make YouTube links open in YouTube ReVanced?

> If you are using MIUI, you may need to use [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After installing it, open it and tap "Manage applications". Then, continue with the steps below:

**3.1)** Go to the App info of the **unpatched** YouTube app and tap on "Set as default" / "Open by default" -> Open supported links, **Off**. (Alternatively, uninstall or disable the unpatched YouTube app.)

**3.2)** Open the App info of YouTube ReVanced and tap on "Set as default" / "Open by default" -> Open supported links, **On**.

**3.3)** Return to the previous page. Tap "Supported web addresses", and turn them all **On**.



### How do I set up the external download feature?

Open YouTube ReVanced -> Settings -> ReVanced -> Player -> External downloads, and enable the `Show external download button` and/or the `Override download action button` toggle(s). You will also need to install the downloader. By default, the downloader will be set to [NewPipe](https://github.com/TeamNewPipe/NewPipe/releases/latest). Another popular downloader is [Seal](https://github.com/JunkFood02/Seal/releases/latest), whose package name is `com.junkfood.seal`. For more extensive info on this topic, see [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq/package_name_of_downloader_appsupdate/).

___

[^1]: To change the patch selection, go to the Advanced section of the ReVanced Manager settings and enable the `Allow changing patch selection and options` toggle. Then, after selecting the YouTube from the app list, press `Select patches` and configure the patches and patch options to your liking. If you don't understand what something does it is best not to tinker with it.