# Android device tree for samsung SM-A346E (a34x)

## Create the directory
    mkdir lineage-24.0; cd lineage-24.0

## Sync lineage-24.0
    repo init -u https://github.com/LineageOS/android.git -b lineage-24.0 --git-lfs; repo sync
 
## Clone
    git clone https://github.com/A34-PeaceZone/lineage_device_samsung_a34-e.git -b lineage-24.0-a device/samsung/a34x; git clone https://github.com/A34-PeaceZone/android_vendor_samsung_a34x-e.git -b A346EXXSADYG1 vendor/samsung/a34x

## Build
    . build/envsetup.sh; export ALLOW_MISSING_DEPENDENCIES=true; lunch lineage_a34x-cp1a-eng; brunch a34x

```
#
# Copyright (C) 2025 The LineageOS Project
#
# SPDX-License-Identifier: Apache-2.0
#
```
