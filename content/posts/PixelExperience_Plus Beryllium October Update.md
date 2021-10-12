+++
date = "2021-10-12"
title = "PixelExperience/Plus Beryllium October Update"
description = "October Update"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Device Specific:**
    * October security patch
    * Fixed the smoothness of brightness transitions
        * brightness now changes in the smallest steps possible, so lower brightness range adjustment no longer feels choppy
        * the effect is similar to the hack at the end of android10, but the implementation is much better
    * Improved the double click haptic feedback to actually feel like a double click
        * you can try it by putting a wrong finger on the fingerprint sensor
    * Tweaked the default thermal profile to hotplug two big CPU cores when the device is really hot
        * in terms of thermal mitigation, offlining two CPU cores is a lot more effective than throttling frequencies
        * when the device is under thermal pressure, having two big cores at relatively higher frequencies is generally more advantageous than having four big cores with lower frequencies
        * the gaming profile (under Settings/Battery/Thermal profiles) remains unchanged
    * Misc fixes and translation updates

* **Etude kernel:**
    * Linux 4.9.286
    * merged CAF tag LA.UM.9.8.r1-04000-SDM710.0 with fix on cdsp regression
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

**NOTE**
* You can dirty flash normal version over previous BETA builds but clean flash is recommended for installing Plus version.
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)