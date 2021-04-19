+++
date = "2021-04-19"
title = "PixelExperience/Plus Beryllium April Update"
description = "April Update"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Feature Update Highlights:**
    * April security patch
    * Fixed the issue of weather information not showing up in “At a glance” on the home screen of Pixel Launcher
    * Improved Face Unlock. The issue of front camera being occupied should happen less frequently. 
    * Devices will only use dark boot animation from now on
    * Translation updates
    * Performance and stability improvements

* **Device Specific:**
    * Adjusted thermal configs to delay CPU frequency drop and smoothen the thermal throttling curve
    * Implemented dynamic thermal profile to work with Pixel thermal engine (only the gaming profile is available besides the default profile, because other use cases are covered well enough by the default profile)
    * Updated telephony blobs from pyxis 21.3.31 to fix random qtibus crashes in the background
    * Stopped enforcing s2idle from userspace init script so the kernel can suspend to RAM for better idle battery drain
    * Some other under-the-hood improvements

* **Etude kernel:**
    * Linux 4.9.267
    * some upstream fixes of cpufreq_stats
    * fixed an issue where the frequency of big CPU cores is locked to a maximum of 1286MHz; the frequency of the big cluster is supposed to be restricted under 1286MHz if you battery is at or below 10%, as part of Qualcomm’s thermal mitigation, but on previous versions, the frequency restriction was not removed after the phone is charged above 10%
    * default to suspend to RAM instead of s2idle (suspend to idle) for around a 25% reduction of idle battery drain
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

**NOTE**
* You can dirty flash normal version over previous BETA builds but clean flash is recommended for installing Plus version.
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)