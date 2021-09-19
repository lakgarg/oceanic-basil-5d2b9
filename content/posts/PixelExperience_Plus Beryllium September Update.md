+++
date = "2021-09-19"
title = "PixelExperience/Plus Beryllium September Update"
description = "September Update"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Device Specific:**
    * September security patch
    * SafetyNet should be passing again
    * Misc fixes and translation updates

* **Etude kernel:**
    * Linux 4.9.282
    * tweaked the haptic intensity for the tick effect
    * DO NOT use a third party kernel without proper support for Pixel thermal hal
    * Rewrote the QTI aidl vibrator HAL to implement haptic effects for QPNP Haptics driver
        * now the vibrator can perform predefined haptic effects instead of doing duration-based vibrations only
        * some operations (the back gesture for example) will have new haptic feedbacks; some existing haptic feedbacks are more accurate and concise, like the long press on home screen and the silent/vibrate toggle in the volume panel

**NOTE**
* You can dirty flash normal version over previous BETA builds but clean flash is recommended for installing Plus version.
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)