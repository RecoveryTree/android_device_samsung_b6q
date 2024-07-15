# TWRP Device Tree for Samsung Galaxy Z Flip 6

## For Decryption
Not Available now.

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/Archer3770/twrp_device_samsung_b6q device/samsung/b6q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_b6q-eng
mka recoveryimage
```
