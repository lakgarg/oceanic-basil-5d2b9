+++
date = "2021-03-08"
title = "EvolutionX-5.5 Beryllium UNOFFICIAL"
description = "March Update"
katex = true
series = ["EvolutionX", "Beryllium"]
+++

![image](https://pbs.twimg.com/profile_banners/1106906709786656768/1610373686/1500x500)

## Changelog:
* **EvolutionX-v5.5 Updates:**
    * March security patch
    * vendor: Add back FaceUnlock support
    * Evolver: Allow scheduling always on display
    * SystemUI: Introduce dynamic VoLTE & VoWiFi icons
    * apex: Update from RQ2A.210305.006
    * Fix inconsistent system app icon colors
    * Switch to using AOSP DocumentsUI (Files app)
    * PixelPropsUtils: Remove gms spoof
    * Fixed SystemUI crash when navbar is hidden and navbar pulse is on
    * Introduced 404 IDE clock
    * Added more Pixel Sounds
    * Fixed issues with VoWiFi icon
    * Many under-the-hood fixes

* **Etude kernel: Op.11 No.2**
    * Linux 4.9.260
    * merged CAF tag `LA.UM.9.3.r1-01000-sdm845.0`
    * kgsl: moved fenced write outside spinlock and avoid busy waiting for it to finish
    * kgsl: removed ringbuffer submission profiling code
    * sde: remove VBIF debug code upon commit
    * page_alloc: consider high-atomic reserve in watermark fast
    * wireguard 1.0.20210219
    * used –lto-O3 for LLD
    * limited LLVM IR inlining during LTO to reduce kernel binary size
    * merged module sections with LTO
    * fixed a wrong PM operation in ICNSS
    * enabled inline spinlock
    * enabled Nintendo Joy-Con support in kernel
    * dropped simple_lmk and brought back PSI/MEMCG
    * removed /proc/config.gz hacks that are no longer needed
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

## Instructions:
**First Time Install / Clean Flash**
* Install the latest custom recovery
* Format data
* After formatting data, you may have to reboot again to recovery
* Wipe system & data & cache & dalvik cache
* Install ROM
* Reboot to system

**Update / Dirty Flash**
* Boot into recovery
* Flash the ROM
* Reboot to system & #KeepEvolving

**NOTE**
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps, Vendor and firmware are included.

`File Name: EvolutionX_5.5_beryllium-11-20210308-0843-UNOFFICIAL.zip`

[**Download**](http://dl.lakshaygarg.in/ROMs/Beryllium/EvolutionX) **|** [**Telegram Group**](https://t.me/uoEvoXPocoF1)