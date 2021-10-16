+++
date = "2021-02-15"
title = "EvolutionX-5.4 11.0 20210215-1726 UNOFFICIAL Beryllium Build"
description = "Febraury Update"
katex = true
series = ["EvolutionX", "Beryllium"]
+++

![image](https://pbs.twimg.com/profile_banners/1106906709786656768/1610373686/1500x500)

## Changelog:
**EvolutionX Updates:**
* February security patch
* Adjusted paddings
* Evolver: brought back lockdown button
* Added more clocks
* Fixed a SystemUI crash when connecting to some Bluetooth devices
* Fixed incorrect default APN configs for Vodafone AU
* Phone ringtone settings for duo SIM
* Brought back long screenshot
* Made Evolver preferences to be searchable
* Some fixes on ambient pulse

**Device Side:**
* Etude kernel: Op.11 No.2
    * Linux 4.9.257
    * merged CAF tag LA.UM.9.3.r1-00700-sdm845.0
    * backported suspend stats sysfs node
    * DO NOT use a third party kernel without proper support for Pixel thermal hal
* Adjusted statusbar paddings
* Satisfied the graceful shutdown of light devices in light HAL
* Turned pinner on for camera
* Added vector icons for parts
* Only show one big core and one little core in overlay through CPUInfo QS tile, to avoid cluttering up screen space

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

[**Download**](http://dl.lakshaygarg.in/ROMs/Beryllium/EvolutionX) **|** [**Telegram Group**](https://t.me/uoEvoXPocoF1)