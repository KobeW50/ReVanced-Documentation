Information
==
### 1. This document is a guide on how to build ReVanced Extended using the official ReVanced Manager.
### 2. To use the RVX Manager, the following conditions must be met:
- Your device must use the arm64-v8a architecture.
- Your device must be running Android 8.0+.

Common
==
### 0. If you are preparing to install in **ROOT environment**, follow the method below
- remove all YouTube related modules
- remove directories: `/data/adb/service.d`, `/data/adb/post-fs-data.d`, `/data/adb/revanced`
- reboot device

​
### 1. Check the [README.md](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-json-format) of revanced-patches for supported YouTube versions

![support_version](https://user-images.githubusercontent.com/108592928/235959704-399a18fe-65fe-4280-82fe-0ffad955818f.png)

※ For YouTube Music, all versions are supported
​

### 2. Download the supported version of YouTube / YouTube Music from APKMirror and **_install it on your device._**

![ReVanced_Manager3](https://user-images.githubusercontent.com/108592928/235961036-962de06d-b44e-4f06-b2ab-a4f6c3dc7d45.png)

※ You must download the `nodpi` version.


### 3. Download [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest) from my repo and install it on your device.


### 4. Follow the screenshots to proceed with the patch.

![ReVanced_Manager4](https://user-images.githubusercontent.com/108592928/202160529-5a62e8ed-40c6-444f-9ad9-447868a29396.png)

![ReVanced_Manager5](https://user-images.githubusercontent.com/108592928/202160603-00138b03-821a-4ca8-b83a-57accc054f31.png)

※ You can include or exclude all patches.

※ Read [this document](https://github.com/inotia00/revanced-documentation/wiki/Options-Information-about-the-patch) for a list of patches you can include or exclude.

NON-ROOT environment
==
When patching, please **include** the following patches

- **`MicroG Support`** (YouTube)

- **`Music MicroG Support`** (YouTube Music)


ROOT environment
==
When patching, please **exclude** the following patches

- **`MicroG Support`** (YouTube)

- **`Music MicroG Support`** (YouTube Music)

I recommend installing the [Detach Magisk module](https://forum.xda-developers.com/t/module-detach3-detach-market-links.3447494/) after patching.

※ [Detach Magisk module](https://forum.xda-developers.com/t/module-detach3-detach-market-links.3447494/) prevents automatic updates by Google Playstore. (Prevent crashes from occurring in the ROOT environment)