+++
date = "2022-07-22"
title = "PixelExperience 12.1 / Plus July Update Beryllium"
description = "Android 12.1 / Plus"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/hc3vHzV/PE12-RGB.png)

## Changelog:
* **Rom Side Changes:**
    * July security patch
    * The system updater app will free up its storage after OTA
    * Fixed the issue of Google’s SystemUpdate constantly retrying in the background, draining battery and building heat.
    * Updated lots of APNs

* **Etude kernel: Op.12 No.4:**
    * Linux 4.9.322
    * massive backport of the kernel random number generator stack from upstream common kernel
    * fixed several conflicts caused by the random stack backport
    * disabled qcom’s early random initializer because it is no longer needed
    * use ascii-armor canary to prevent buffer overflow from overwriting canary in fork
    * Wireguard 1.0.20220627 to go with the new random stack
    * fixed several section mismatches in qcom’s regulator drivers
    * fixed an incorrect asoc bound check that potentially causes echo in speaker-mode phone calls
    * DO NOT use another kernel. Just don’t.

* **Device Side Changes:**
    * Moved the fingerprint HAL process out of system-background task group for cpuset
        * this should significantly reduce the fingerprint unlock latency in some cases
    * Corrected the audio HAL service name in power HAL’s restart script

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