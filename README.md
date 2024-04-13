# PixelOS Fork (ye)

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/Yohan-Black/manifest.git -b fourteen --git-lfs
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch aosp_devicecodename-ap1a-userdebug
```

Start compilation

```bash
make bacon  -j$(nproc --all)
```
