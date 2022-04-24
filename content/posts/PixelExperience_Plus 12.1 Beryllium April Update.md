+++
date = "2022-04-24"
title = "PixelExperience 12.1 / Plus April Update Beryllium"
description = "Android 12.1 / Plus"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/hc3vHzV/PE12-RGB.png)

## Changelog:
* **Device Specific:**
    * April security patch
    * Fixed charging animation not appearing
    * Fixed unlock sound playing repeatedly
    * Fixed incorrect APN configs for Vodafone NL
    * Updated translations

* **Etude kernel: Op.12 No.3:**
    * Linux 4.9.310
    * CodeLinaro tag `LA.UM.10.3.r1-01700-sdm845.0`
    * adapted qcom's kgsl perf counter change to non-privileged scratch buffer
    * ported compiler friendly vectorization for XOR from mainline kernel
    * ported arm64-specific crc32_be optimization from mainline kernel
    * ported Arm Optimized Routines for strcmp and strncmp from mainline kernel
    * merged and adapted lots of branch prediction hardening code from android common kernel
    * fixed qcom's PSCI BP hardening mitigation for kryo2xx/3xx cores after new macro changes and fine-grained capabilities
    * built with the latest LLVM Clang 15.0
    * DO NOT use another kernel. Just don't.

* **Plus edition has features including but not limited to:**
    * Gesture customizations
    * Power and volume button actions
    * Network traffic indicator
    * Statusbar customizations
    * Lockscreen customizations
    * Per-app volume control
    * Brightness related options
    * LiveDisplay

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