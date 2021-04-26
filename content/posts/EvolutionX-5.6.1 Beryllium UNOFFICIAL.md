+++
date = "2021-04-26"
title = "EvolutionX-5.6.1 Beryllium UNOFFICIAL"
description = "April Update"
katex = true
series = ["EvolutionX", "Beryllium"]
+++

![image](https://pbs.twimg.com/profile_banners/1106906709786656768/1610373686/1500x500)

## Changelog:
* **EvolutionX-v5.6.1 Updates:**
    * April security patch
    * Added QS and SysUI colors to Evolver and allowed QS theme to change according to wallpaper colors
    * Added preview to theme settings
    * Added screenshot quality settings
    * Some more QS tint styles
    * Face unlock improvements from PE
    * More changes from android S DP3
    * Brought back lock screen visualizer
    * Added Smart Cutoff feature to limit charging based on battery temperature, and improved the logic to work with Smart Charging (based on battery level) together

* **Device Specific:**
    * Adjusted thermal configs to delay CPU frequency drop and smoothen the thermal throttling curve
    * Implemented dynamic thermal profile to work with Pixel thermal engine (only the gaming profile is available besides the default profile, because other use cases are covered well enough by the default profile)
    * Updated telephony blobs from pyxis 21.3.31 to fix random qtibus crashes in the background
    * Stopped enforcing s2idle from userspace init script so the kernel can suspend to RAM for better idle battery drain
    * Updated blobs and firmware from MIUI China Stable V12.0.3.0
    * Updated priv-app permission whitelist for HotwordEnrollment
    * Some other under-the-hood improvements

* **Etude kernel:**
    * Linux 4.9.267
    * some upstream fixes of cpufreq_stats
    * fixed an issue where the frequency of big CPU cores is locked to a maximum of 1286MHz; the frequency of the big cluster is supposed to be restricted under 1286MHz if you battery is at or below 10%, as part of Qualcomm’s thermal mitigation, but on previous versions, the frequency restriction was not removed after the phone is charged above 10%
    * default to suspend to RAM instead of s2idle (suspend to idle) for around a 25% reduction of idle battery drain
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

`File Name: EvolutionX_5.6.1_beryllium-11-20210424-1747-UNOFFICIAL.zip`

[**Download**](http://dl.lakshay.wtf/ROMs/Beryllium/EvolutionX/) **|** [**Telegram Group**](https://t.me/uoEvoXPocoF1)