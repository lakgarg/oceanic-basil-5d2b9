+++
date = "2021-02-07"
title = "PixelExperience 11.0 20210207-0918 OFFICIAL Beryllium Beta Build"
description = "Febraury Changelog"
katex = true
series = ["PixelExperience", "Beryllium"]
+++

![image](https://i.ibb.co/ZXxNTPk/pixel-experience-android-11.png)

## Changelog:
* **Feature Update Highlights:**
    * Febraury security patch

* **Device Side:**
    * Fixed a SystemUI crash when connecting to some Bluetooth devices
    * Switched to MIUI V12.0.2.0
    * Added GCAM Go as default instead of Snap (Updatable through Play Store)
    * Update Vendor and Firmware Blobs from MIUI V12.0.3.0
    * Imported RenderScript blobs from Pixel 3 XL
    * Configured SQLite journal to use MEMORY mode
        * about 2x performance increase in SQLite insert/update/delete
    * Satisfied the graceful shutdown of light devices in light HAL
    * Created and symlinked a dummy /metadata/apex to fix Google Play system update
        * Google moved the apex sessions directory from /data/apex/sessions to /metadata/apex/sessions
        * we do not have a metadata partition out of the box
        * thus a dummy directory is created to satisfy the requirement
        * Note: there may be multiple Google Play system updates since October 2020, and your phone may need multiple reboots to install them. You may see a “try again” after you press the reboot button for the second time, and that is because Google Play stops reboot caused by system update if the previous reboot was within 15 minutes. It was intended to prevent infinite reboot during a bootloop (and yes it is stupid in this case). Just reboot manually and the update will install fine.

* **Etude kernel:**
    * Linux 4.9.256
    * hacked LINUX_VERSION_CODE to maintain compatibility with drivers and modules after the SUBLEVEL goes beyond 8 bits (255 max)
    * merged CAF tag LA.UM.9.3.r1-00700-sdm845.0
    * wireguard 1.0.20200124
    * backported suspend stats sysfs node
    * cpufreq: reverted average capacity calculation fix due to performance regression
    * sched: unified spare capacity calculation
    * sched: prefer a CPU in a more shallow idle state to achieve faster wake-up and higher efficiency
    * DO NOT use a third party kernel without proper support for Pixel thermal hal

**NOTE**
* Users might face minimal Jitters right after updating, But give it some time, an hour or two and it'll be totally alright.
* Do not flash any other kernel on A11. First check if it supports Pixel Thermals.
* For google Camera, Use any Camera Mod. Parrot043's and San1ty's Builds Work good with PocoF1, But Anyone can try any mods. Find the Apks here (https://www.celsoazevedo.com/files/android/google-camera/).
* Gapps are included. Vendor and firmware are included.

[**Download**](https://download.pixelexperience.org/beryllium) **|** [**XDA**](https://forum.xda-developers.com/t/rom-official-11-0-beryllium-pixel-experience-aosp-2020-12-23.4196119/)