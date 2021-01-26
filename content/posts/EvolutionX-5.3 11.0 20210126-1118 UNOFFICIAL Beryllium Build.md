+++
date = "2021-01-25"
title = "EvolutionX-5.3 11.0 20210126-1118 UNOFFICIAL Beryllium Build"
description = "New Update"
katex = true
series = ["EvolutionX", "Beryllium"]
+++

![image](https://pbs.twimg.com/profile_banners/1106906709786656768/1610373686/1500x500)

## Changelog:
**Etude kernel:**
* Linux 4.9.253
* rolled back to qcacld from `LA.UM.8.3.r1-08800-sdm845.0` due to a regression on 160MHz channels of IEEE 802.11ac WiFi
* sched: unified spare capacity calculation
* sched: prefer a CPU in a more shallow idle state to achieve faster wake-up and higher efficiency
* sched: restricted iowait boost to foreground and top-app tasks so that background I/O does not boost cpu frequency unnecessarily
* cpufreq: fixed incorrect average capacity calculation
* limited sched{up,down}migrate tunables to values between 0 and 100

**Device Side:**
* Updated vendor and firmware from MIUI Global Stable V12.0.3.0
* Fixed SafetyNet
* Added GCam Go as default instead of Snap
* Add f2fs support
* Use MIUI 12 build fingerprint
* Imported RenderScript blobs from Pixel 3 XL
* Fixed WifiOverlay and TetheringOverlay to properly target wifi and tethering stack from Google
    * mac address randomization and other platform specific configs are back
* Configured SQLite journal to use MEMORY mode
    * about 2x performance increase in SQLite insert/update/delete
* Allow manually configuring the APN when using China Unicom
* Cleaned up display stack

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

[**Download**](http://dl.lakshay.wtf/ROMs/Beryllium/EvolutionX/) **|** [**Telegram Group**](https://t.me/uoEvoXPocoF1)