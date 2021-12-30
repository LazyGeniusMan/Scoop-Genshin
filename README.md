# Genshin Impact Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Build Status](https://ci.appveyor.com/api/projects/status/8icx0a4299018duy?svg=true)](https://ci.appveyor.com/project/LazyGeniusMan/scoop-genshin "Build Status") [![Excavator](https://github.com/LazyGeniusMan/Scoop-Genshin/actions/workflows/excavator.yml/badge.svg)](https://github.com/LazyGeniusMan/Scoop-Genshin/actions/workflows/excavator.yml)

This repository is a [Scoop](https://github.com/ScoopInstaller/scoop) bucket for Genshin Impact related tools.

How do I install these App?
---------------------------------

### 1. Install Scoop (skip if you have installed scoop)
Follow instruction here: [https://github.com/ScoopInstaller/scoop#installation](https://github.com/ScoopInstaller/scoop#installation)

**TL;DR**
Open Powershell, and then run this to install scoop:
```
iwr -useb get.scoop.sh | iex
```

Note: if you get an error you might need to change the execution policy (i.e. enable Powershell) with:
```
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
```
After that, rerun the command to install scoop.

### 2. Add this bucket to your Scoop (skip if you have added this bucket)
Run (in Powershell):
```
scoop bucket add Scoop-Genshin https://github.com/LazyGeniusMan/Scoop-Genshin
```

### 3. (Optional) enable multi-connection downloads
Run (in Powershell):
```
scoop install aria2
```

### 4. Install the App
Run (in Powershell):
```
scoop install <app-name>
```
List of apps can be found here: [https://github.com/LazyGeniusMan/Scoop-Genshin/tree/main/bucket](https://github.com/LazyGeniusMan/Scoop-Genshin/tree/main/bucket)

How do I manage these App?
---------------------------------

### Check available update
Run (in Powershell):
```
scoop status
```

### Update App
Run (in Powershell):
```
scoop update <app-name>
```

### Remove App old version installation
[WARNING: Make sure your app data/setting is not lost after update, if your app data/setting is lost dont run this command and click this text](https://github.com/LazyGeniusMan/Scoop-Genshin/issues/6)

Run (in Powershell):
```
scoop cleanup <app-name>
```

### Uninstall App
Run (in Powershell):
```
scoop uninstall <app-name>
```

### Tips
You can install, update, cleanup and uninstall multiple app in one command, separate `<app-name>` by space.

For more info, run `scoop -h` or visit [Scoop Documentation](https://scoop-docs.vercel.app/)

Genshin Impact Tools you are looking for isn't in the bucket ?
----------------------------------

To add a new app, you need to make something called an app manifest. If you want to request an app, you can open an issue. If you want to make it yourself and open a PR, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).

----
