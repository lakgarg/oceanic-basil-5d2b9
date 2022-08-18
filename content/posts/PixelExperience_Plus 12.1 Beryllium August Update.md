+++
date = "2022-08-18"
title = "PixelExperience 12.1 / Plus August Update Beryllium"
description = "Android 12.1 / Plus"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/hc3vHzV/PE12-RGB.png)

## Changelog:
* **Rom Side Changes:**
    * August security patch
    * The boot animation now follows Monet color theme as well
    * Other misc fixes

* **Etude kernel: Op.12 No.4:**
    * Linux 4.9.325
    * merged LA.UM.10.3.r1-01700-sdm845.0 into techpack/audio
    * fixed a race condition in qcom’s early random pool initialization
    * re-enabled qcom’s early random initialization
    * cleaned up several unused drivers and firmware in kernel
    * dropped unnecessary virtual framebuffer support
    * DO NOT use another kernel. Just don’t.

* **Device Side Changes:**
    * Dropped the unnecessary virtual framebuffer from kernel cmdline
    * Removed the boot-time IO read ahead tuning and settled on a static read-ahead value for dm devices
        * Google claims that some of the values may not be properly reset after boot, so an aggressively large boot-time read-ahead value may persist after boot and incur more memory pressure
    * Fixed the issue of “Optimization profile” app list sometimes not showing all the apps
        * also improved the layout and the overall smoothness when scrolling

**NOTE**
* Force Encryption is Enabled by Default.
* You can dirty flash from my previous PE 12 / 12.1 builds. You can dirty flash the Plus edition on top of PE 12 / 12.1 regular builds.
* You cannot upgrade from android 11 directly. Formatting data is required.
* Clean Flash is MANDATORY if flashing for first time!
* Any Recovery present will be overridden by PE recovery in order to make OTA updates work as other recoveries currently doesn't supports Decryption!
* Encrypted users are RECOMMENDED not to use Custom Recoveries! Or else OTA won't work and have to update manually through adb sideload or external storage.
* If you are a decrypted user flash Latest TWRP again and follow the steps to update ROM manually.
* OTA doesn't work for Decrypted Users
* Flash Latest TWRP first before proceeding for installation!

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-12-0-beryllium-pixel-experience-aosp-2022-01-19.4390697/)