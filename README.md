# OReality Audio realme GT 6T Magisk Module

## DISCLAIMER
- OPlus apps and blobs are owned by OPlus™.
- The MIT license specified here is for the Magisk Module only, not for OPlus apps and blobs.

## Descriptions
- Equalizer sound effect ported from realme GT 6T (RE606FL1) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Global type sound effect

## Sources
- https://dumps.tadiphone.dev/dumps/realme/re606fl1 qssi_64-user-14-UP1A.231005.007-1718122606118-release-keys--IN
- libmagiskpolicy.so: Magisk (stable) 30.7 (30700)

## Changelog

v0.8
- Support NoMount metamodule
- Update libmagiskpolicy.so from Magisk (stable) 30.7 (30700)
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/
- Removes conflicted weird modules
- Does not disable raw playback (You can use Audio Compatibility Patch Reborn Magisk Module instead)

v0.7
- Fix wrong target in latest KernelSU

v0.6
- Tidy up aml.sh
- Exclude \*audio\*effects\*haptic\*.xml
- Abort installation if fail to mount mirror system
- Fix wrong file permissions in some ROMs

v0.5
- Fix crashes in SDK 32 and bellow
- Improve /odm and /my_product support detection

v0.4
- Add Action button to clear apps caches
- Fix architecture detection
- Fix bug in uninstall.sh
- Apply effect to rerouting and patch stream by default for game apps

v0.3
- Android Emulator support

v0.2
- Fix selinux denials

v0.1
- Initial release

## Screenshots
https://t.me/androidryukimods/2327

## Requirements
- arm64-v8a or armeabi-v7a architecture
- Android 10 (SDK 29) and up
- HIDL audio service
- Magisk or Kitsune Mask or KernelSU or Apatch installed
- OPlus Core Magisk Module installed in non-OPlus ROM https://github.com/reiryuki/OPlus-Core-Magisk-Module

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs or https://github.com/KernelSU-Modules-Repo/magic_mount_rs or https://github.com/KernelSU-Modules-Repo/hybrid_mount or https://github.com/maxsteeel/nomount first depending on ROM compatibility
- Install OPlus Core Magisk Module first if you are in non-OPlus ROM: https://github.com/reiryuki/OPlus-Core-Magisk-Module
- Install this module via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Install AML Magisk Module https://t.me/ryukinotes/34 only if using any other else audio mod module
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot afterwards
- If you have an issue with your in-built Spatial Audio, then install AOSP Sound Effects Remover also: https://github.com/reiryuki/AOSP-soundfx-Remover-Magisk-Module

## Optionals
- https://t.me/ryukinotes/69
- Global: https://t.me/ryukinotes/35
- Stream: https://t.me/ryukinotes/52

## Troubleshootings
Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- @HuskyDG
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


