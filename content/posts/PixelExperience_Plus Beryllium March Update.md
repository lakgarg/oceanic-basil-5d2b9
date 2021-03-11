+++
date = "2021-03-11"
title = "PixelExperience/Plus Beryllium March Update"
description = "March Update"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Feature Update Highlights:**
    * March security patch
    * Implemented new Face Unlock, with support for 3rd apps
    * Added ability to select custom ringtone for 2nd sim card
    * Added support for NTFS/EXFAT on USB Disks and sdcard
    * Improved animations when unlocking
    * Add support for Bluetooth SBC Dual Channel
    * Others improvements

* **Device Specific:**
    * Brought back Livedisplay
    * Ported dex2oat threads and cpu-set power hints under various thermal conditions from Pixel 5
    * Tweaked INTERACTION power hints to be more efficient according to freqbench results
    * Added Adaptive Battery power hints from Pixel 3/XL March 2021 feature drop
    * Cleaned up duplicated values and unused entries in init script

* **Etude kernel:**
    * Linux 4.9.260
    * merged CAF tag LA.UM.9.3.r1-01000-sdm845.0
    * f2fs: increased min_fsync_blocks to 20
    * enabled BPF JIT
    * binder: avoided printing debug by default
    * kgsl: used lock-less list for page pools
    * sde: avoided dynamically allocating memory for CRTC check
    * sde: skipped heavy autorefresh checks
    * sde: avoided clearing dim layers unnecessarily
    * kgsl: moved fenced write outside spinlock and avoid busy waiting for it to finish
    * kgsl: removed ringbuffer submission profiling code
    * sde: remove VBIF debug code upon commit
    * page_alloc: consider high-atomic reserve in watermark fast
    * wireguard 1.0.20210219
    * used –lto-O3 for LLD
    * limited LLVM IR inlining during LTO to reduce kernel binary size
    * merged module sections with LTO
    * fixed a wrong PM operation in ICNSS
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

**NOTE**
* You can dirty flash normal version over previous BETA builds but clean flash is recommended for installing Plus version.
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)