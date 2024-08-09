# TWRP Device Tree for Samsung Galaxy S24 Snapdragon(e1q)

## For Decryption
[Install Instructions](https://xdaforums.com/t/sm-s928b-0-userdata_aio-odin-flashable-to-automatically-remove-encryption-make-rom-rw-install-twrp-root-use-on-stock-firmware-unlocked-bootloaders.4660645/)

# Special Thanks 
[Archer](https://github.com/archer3770) For his guide and s24ultra device tree
[jrkruse](https://xdaforums.com/m/jrkruse.1949695/) For userdata aio script.

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/Andy312432/android_device_samsung_sm8650_twrp device/samsung/e1q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_e1q-eng
mka recoveryimage
```
