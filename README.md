# SpotBright
A collection of all known [Windows Spotlight](https://en.wikipedia.org/wiki/Windows_Spotlight) wallpapers.

## Source
### SpotBright
All Spotlight wallpapers are pulled from Bing and cycle periodically.
You can use the app [SpotBright](https://www.microsoft.com/en-us/store/p/spotbright/9nblggh5km22) to download most Spotlight wallpapers.
This repository is a mirror for SpotBright downloads.

### Local
Alternatively you can copy all files from `%LocalAppData%\Packages\Microsoft.Windows.ContentDeliveryManager_cw5n1h2txyewy\LocalState\Assets` into another directory and make them readable by renaming all to JPEG files using the following PowerShell command:
```PowerShell
ren * *.jpg
```
After that you have to sort out unwanted files and you've got all recent Spotlight wallpapers.
