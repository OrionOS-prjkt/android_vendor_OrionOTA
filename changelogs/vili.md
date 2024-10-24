# Changelog October 24, 2024:
## Device:
- Rebased trees with latest changes from lineage
- Add missing blobs
- Migrate sensor HAL to AIDL interface
- Switch to QTI Memtrack AIDL HAL
- Update common blobs from haydn V816.0.6.0.UKKMIXM
- Update vili blobs, firmware and MIUI camera app from V816.0.6.0.UKDMIXM
- Decommonized citsensorservice
- Dolby: Import russian translations
- Lowered gpu boost for expensive rendering to 778Mhz
- Modified thermal-normal.conf for balanced performance, credits to @tanzilw

## Kernel:
- Add idle state sysfs node
- Set idle state correctly
- Add sysfs node for trigger wake up early
