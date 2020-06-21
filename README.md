-----------------------------------------------------------------------------

<p align="center">
 <img src="https://github.com/WrathOS/Wrath_Extras/blob/master/Banner_1.png" > 
</p>

-----------------------------------------------------------------------------

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/WrathOS/android_manifest -b ten
```
Then to sync up:
================

```bash
repo sync -c -f --force-sync --no-tags --no-clone-bundle -j$(nproc --all) --optimized-fetch --prune
```

Finally to build:
====================

From root directory of Project, perform following commands in terminal


```bash
. build/envsetup.sh
lunch wrath_<devicecodename>-userdebug
make bacon
```
-----------------------------------------------------------------------------

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**RevengeOs**](https://github.com/RevengeOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**Havoc**](https://github.com/Havoc-OS)
 * [**Nitrogen**](https://github.com/nitrogen-project)
-----------------------------------------------------------------------------
