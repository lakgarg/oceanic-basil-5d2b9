+++
date = "2022-03-01"
title = "PixelExperience 12 Febraury Update Beryllium"
description = "Android 12 STABLE"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/hc3vHzV/PE12-RGB.png)

## Changelog:
* **Device Specific:**
    * February security patch
    * Brought back Face Unlock, and it also works in apps using the standard biometric authentication mechanism
    * Fixed some statusbar paddings
    * Translation updates and misc bug fixes
    * Brought back qcom wfd implementation
    * Properly disabled surfaceflinger backpressure propagation to reduce jank in certain scenarios
    * Updated adreno blobs from LA.UM.9.3.r1-02700-sdm845.0
    * Updated parts to newer APIs like TaskStackListener and TaskInfo
    * also fixed some harmless log spams caused by SElinux
    * Whitelisted an intent broadcast for the new ims.apk
    * Dropped obsolete eBPF prop
    * Implemented a boost after fingerprint authentication to speed up the unlocking process and avoid animation janks

* **Etude kernel: Op.12 No.2:**
    * Linux 4.9.303 and CAF tag LA.UM.10.3.r1-00900-sdm845.0
    * upstreamed generic locking/refcount from 4.14
    * ported arm64-specific fast refcount checking
    * enabled HID WACOM driver
    * wireguard 1.0.20211208
    * DO NOT use another kernel. Just don’t.


**NOTE**
* Force Encryption is Enabled by Default.
* Clean Flash is MANDATORY if flashing for first time!
* Any Recovery present will be overridden by PE recovery in order to make OTA updates work as other recoveries currently doesn't supports Decryption!
* Encrypted users are RECOMMENDED not to use Custom Recoveries! Or else OTA won't work and have to update manually through adb sideload or external storage.
* If you are a decrypted user flash Latest TWRP again and follow the steps to update ROM manually.
* OTA doesn't work for Decrypted Users
* Flash Latest TWRP first before proceeding for installation!

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-12-0-beryllium-pixel-experience-aosp-2022-01-19.4390697/)