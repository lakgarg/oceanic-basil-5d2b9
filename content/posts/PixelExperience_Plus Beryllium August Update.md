+++
date = "2021-08-23"
title = "PixelExperience/Plus Beryllium August Update"
description = "August Update"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Device Specific:**
    * August security patch
    * Updated brightness curve
    * Enabled ThinLTO and Whole Program Devirtualization for display HAL
    * Moved kryo385 target from cortex-a53 to cortex-a55+nodotprod in the soong build system to take advantage of extra instructions
    * Updated WFD, DPM, IMS, and RIL system blobs from LA.QSSI.11.0.r1-12100-qssi.0
    * Updated display and media HAL from LA.UM.9.3.r1-02800-sdm845.0
    * Translation updates
    * Minor fixes

* **Etude kernel:**
    * Linux 4.9.280
    * CAF tag LA.UM.9.3.r1-02800-sdm845.0
    * fixed -mcpu target for kryo385 by dropping the dot product instructions
    * backported symbol export inside assembly from upstream 
    * backported modern annotations for assembly functions from upstream
    * backported the latest version of ARM’s optimized routines for arm64 from mainline kernel (Linux 5.13): memcmp, strcmp, strlen, strncmp, memcpy, memmove, and memchr
    * backported support for tagged userspace pointers from upstream
    * enabled driver for the Steam controller
    * backported SELinux fixes and android-specific patches from Linux 4.14
    * enabled fast multipliers and flatmem for arm64
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

**NOTE**
* You can dirty flash normal version over previous BETA builds but clean flash is recommended for installing Plus version.
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)