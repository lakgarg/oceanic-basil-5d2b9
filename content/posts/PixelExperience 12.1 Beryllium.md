+++
date = "2022-04-03"
title = "PixelExperience 12.1 March Update Beryllium"
description = "Android 12.1 STABLE"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/hc3vHzV/PE12-RGB.png)

## Changelog:
* **Device Specific:**
    * March security patch
    * Rebased over Android 12L source code
    * Added call recording support
    * Fixed biometric authentication on some apps – mainly banking apps
    * Fixed several face unlock issues. For example, initial setup wizard no longer requires you to enroll in face unlock when you have lockscreen password
    * Removed combined network signal icon cluster 
    * Updated translations

* **Etude kernel: Op.12 No.2:**
    * Linux 4.9.309
    * CAF tag LA.UM.10.3.r1-01000-sdm845.0
    * set compiler flag to optimize for cortex-a55 to avoid performance regression on the in-order little cluster
    * DO NOT use another kernel. Just don't.

**NOTE**
* Force Encryption is Enabled by Default.
* Clean Flash is MANDATORY if flashing for first time!
* Any Recovery present will be overridden by PE recovery in order to make OTA updates work as other recoveries currently doesn't supports Decryption!
* Encrypted users are RECOMMENDED not to use Custom Recoveries! Or else OTA won't work and have to update manually through adb sideload or external storage.
* If you are a decrypted user flash Latest TWRP again and follow the steps to update ROM manually.
* OTA doesn't work for Decrypted Users
* Flash Latest TWRP first before proceeding for installation!

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-12-0-beryllium-pixel-experience-aosp-2022-01-19.4390697/)