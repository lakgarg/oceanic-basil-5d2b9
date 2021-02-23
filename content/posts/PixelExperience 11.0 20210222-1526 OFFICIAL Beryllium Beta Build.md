+++
date = "2021-02-23"
title = "PixelExperience 11.0 20210222-1526 OFFICIAL Beryllium Beta Build"
description = "Final Beta Changelog"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Feature Update Highlights:**
    * Fixed crashes on the system update interface. Note that this takes effect after you update to the new build. If you happen to run into crashes now, tap the top right button to delete old downloads and re-download again.
    * Dropped apex because it does not offer any meaningful features to us
    * Added default APN config for rakuten.jp
    * Reverted the three-row QS changes

* **Device Side:**
    * Enabled the improved userspace lmkd on Android 11
    * Updated wifi display system blobs from `LA.QSSI.11.0.r1-09400-qssi.0`
    * Cleaned up and updated telephony blobs from `LA.QSSI.11.0.r1-09400-qssi.0`
    * Parts: used all shared resources and moved to static libs for custom strings
    * Turned pinner on for camera
    * Added vector icons for parts

* **Etude kernel:**
    * Linux 4.9.257
    * merged CAF tag `LA.UM.9.8.r1-03600-SDM710.0` and branch `kernel.lnx.4.9.r27-rel`
    * enabled Nintendo Joy-Con support in kernel
    * dropped simple_lmk and brought back PSI/MEMCG
    * removed /proc/config.gz hacks that are no longer needed
    * enabled inline spinlock
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

**NOTE**
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)