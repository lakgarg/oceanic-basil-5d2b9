+++
date = "2021-01-19"
title = "PixelExperience 11.0 20210119-0516 OFFICIAL Beryllium Beta Build"
description = "January Changelog"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Feature Update Highlights:**
    * January security patch
    * Fixed crashes on AR Core
    * SafetyNet should pass again

* **Device Side:**
    * Fix Hotword detection with Screen OFF
    * Adjust status bar paddings
    * Enabled iwlan legacy mode
    * Switched to QTI BT stack
    * aptX tws+ codec support is back
    * Built libwfdaac_vendor from source

* **Etude kernel:**
    * Linux 4.9.252
    * merged CAF tag `LA.UM.9.3.r1-00500-sdm845.0` into kernel
    * sched: restricted iowait boost to foreground and top-app tasks so that background I/O does not boost cpu frequency unnecessarily
    * cpufreq: fixed incorrect average capacity calculation
    * limited sched{up,down}migrate tunables to values between 0 and 100
    * backported arm64 optimized assembly routine from mainline kernel: NEON accelerated XOR implementation, faster checksum, consistently enabling crc32 extension, and bug fixes in copy
    * use atomic update for clkgate_enable so that frequent toggling from power hint does not cause a timeout
    * use WQ_HIGHPRI for UFS gating work
    * minimized qos remap updates in sde plane
    * updated sdFAT to 2.4.5
    * inlined spinlock function family
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

**NOTE**
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)