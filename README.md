# TWRP for the Samsung Galaxy J7 2016

TWRP device tree for Samsung Galaxy J7 2016 (`j7xelte`), based on the TWRP AOSP 12.1 manifest.

## Build
```bash
source build/envsetup.sh
lunch twrp_j7xelte-eng
mka recoveryimage
```
The recovery image is `out/target/product/j7xelte/recovery.img`.
