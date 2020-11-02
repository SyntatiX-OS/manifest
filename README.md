 SyntatiX-OS
==============

Time to get started
-------------------

To get started with Android/LineageOS, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

Let's initialize our ROM source.
```
repo init -u https://github.com/SyntatiX-OS/manifest.git -b sR
```
To sync all our stuffs:
```
repo sync --force-sync -j32
```

Before building: 

```
Add this flag in syntatix_yourdevicename.mk: 
```

```
TARGET_DEVICE := yourdevicename
```

Do Define GApps arch:  

```
TARGET_GAPPS_ARCH := arm / arm64
```
