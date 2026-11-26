# TesseraOS

Android 16 custom ROM based on LineageOS 23.2 with a clean-room Windows Phone 8.1 Metro UI implementation, dynamic system-wide accent engine, and Selawik typography.

## Source Sync

```bash
repo init -u https://github.com/TesseraOS-Android/android.git -b 16.0 --git-lfs
repo sync -c --no-clone-bundle --optimized-fetch --prune
```

## Build (Nothing Phone (1) - Spacewar)

```bash
source build/envsetup.sh
lunch tessera_Spacewar-bp4a-userdebug
mka bacon
```

## Credits & Attribution

- Android Open Source Project (AOSP)
- LineageOS Project
- TheMuppets
- Microsoft Selawik Font (MIT License)
- KernelSU (backslashxx/KernelSU)