# Changelog 12 October 2024:
- Synced with latest source

# Changelog 28 August 2024:
- Leica Camera fully working now and Updated to 5.0 Beta 8.1
- Update kernel compiler to clang-r510928 by Google
- Set LTE+ threshold bandwidth to 0 by default
- Enable voLTE/voWIFI/ViLTE for Portugal networks
- Enable VoLTE/ViLTE/VoWiFi for entire 470 mcc
- Update CarrierConfig to NOS 2.6
- Disable phantom processing by default for fix some apps issue like a termux got error signal 9
- Enable USB Debugging by default after boot
- Build libaudio-resampler
- Fixup audio io policy voip_rx flags
- Increase In-call earpiece volume
- Fix low mic volume on voip
- Use QCOM implementation for audio effects
- Enable video pause workaround for video calling
- Define OEM fast charge sysfs node
- Enable powerhint parsing after boot completion
- Switch to Shiryu:[Raghael] for kernel

# Changelog 23 July 2024: 
- Updated LeicaCam to v7.5(Hotfix2) Thanks to @itzdfplayer_stash
- Fix notifications sound after reboot
- More

# Changelog 15 July 2024: 
- Initial official release
- Firmware already included
- Leica cam included and fixed EIS and Portrait, maybe bugs on HDR mode and front camera video mode.
- Switch to common libqti-perfd-client and power-libperfmgr
- Set double tap mode via powerhint
- Use the fragment for QTI vibrator HAL
- Fix PowerOffAlarm
- Spatial Audio Optimization
- Use latest google clang for kernel compiler
- Switch to Shiryu:[Claire] kernel
- Integrity pass by default (signed)
- KSU not included
- Revamped XiaomiParts
- Initial UQPR3
