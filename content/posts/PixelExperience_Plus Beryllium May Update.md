+++
date = "2021-05-19"
title = "PixelExperience/Plus Beryllium May Update"
description = "May Update"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Device Specific:**
    * May security patch
    * Ported extreme battery saver power hints
        * enabling extreme battery saver now limits the maximum cpu frequency
    * Shipped a disabled VBMeta image
    * Synced several wifi configs, media codec performance configs, audio configs, and audio props changes with CAF
    * Dropped unneeded libI420colorconvert libraries
    * Translation updates
    * Some other under-the-hood improvements

* **Etude kernel:**
    * Linux 4.9.268
    * merged CAF tag LA.UM.9.3.r1-01700-sdm845.0
    * correctly report fingerprint sensor type to /proc/hwinfo
    * synaptics touchscreen driver: ported two fixes of potential mutex deadlock in buffer allocation
    * enabled secure touch for touchscreen driver
    * disabled unused touchscreen drivers to reduce kernel binary size
    * wireguard 1.0.20210424
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

**NOTE**
* You can dirty flash normal version over previous BETA builds but clean flash is recommended for installing Plus version.
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)