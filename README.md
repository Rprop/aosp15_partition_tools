# aosp15_partition_tools
Prebuilt statically linked partition_tools (lpmake, lpunpack, ext2simg, simg2img, etc.) for Linux &amp; Windows from android-15.0.0_r25

# build
```
source build/envsetup.sh && lunch aosp_arm64-trunk_staging-eng
mmm -j64 system/extras/partition_tools
mmm -j64 system/core/libsparse
mmm -j64 external/e2fsprogs/contrib/android
```
