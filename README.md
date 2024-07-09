# TWRP Device Tree for Samsung Galaxy S23

## For Decryption
[Install Instructions](https://xdaforums.com/t/sm-s911b-0-one-ui-6-1-userdata_aio-odin-flashable-to-remove-encryption-make-rom-rw-install-twrp-root-use-on-stock-firmware-unlocked-bootloaders.4610067/)

# Special Thanks 
[jrkruse](https://xdaforums.com/m/jrkruse.1949695/) For userdata aio script.

[Edward](https://github.com/edward0181) For help me.

## Kernel source
https://github.com/edward0181/android_kernel_samsung_sm8550

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/Archer3770/twrp_device_samsung_dm1q device/samsung/dm1q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_dm1q-eng
mka recoveryimage
```