---
sticker: lucide//bean
tags:
  - Flutter
  - Android-Studio
color: "#f7b731"
_contexts:
  - Installation android studio on linux
---
1. Download [Android Studio](https://developer.android.com/studio)
2. Unzip file downloaded.
3. Move files to  `usr/local`.
```shell
sudo mv ~/Downloads/android-studio /usr/local
cd /usr/local/android-studio/bin
./studio.sh   
```
1. Add desktop entry to access from menu.
```shell
sudo nano /usr/share/applications/android-studio.desktop
```
```shell
[Desktop Entry]
Type=Application
Name=Android Studio
Icon=/usr/local/android-studio/bin/studio.png
Exec="/usr/local/android-studio/bin/studio.sh"
Comment=Android Stidio Desktop App
Categories=Development;Code;
```