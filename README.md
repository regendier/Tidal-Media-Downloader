# Tidal-Media-Downloader

Tidal-Media-Downloader is an application that lets you download videos and tracks from Tidal. You can just copy-paste ID of any videos, tracks, playlists or albums and download them directly to a format of your choice. It supports two version: tidal-dl(python) and tidal-gui(C#-Only Windows)   

## Download

- [tidal-dl.exe](https://github.com/yaronzz/Tidal-Media-Downloader/tree/master/TIDALDL-PY/exe)
- [tidal-gui.exe](https://github.com/yaronzz/Tidal-Media-Downloader/tree/master/TIDALDL-UI/TIDALDL-UI/bin/Release)
- tidal-dl by pip
  ``` python
  root:~# pip install tidal-dl --upgrade
  root:~# tidal-dl 
  ```

## Requirement
- Python 3.7 : If you install tidal-dl by pip
- FFmpeg : If you want to download video or set tarck metadata

## Features
### Python(cmd)
- Supports single videos, playlists, tracks, artist-albums and albums
- Selectable video resolution and track quality
- Multiple downloads
### C#(gui)
- Supports single videos, tracks and albums
- Selectable video resolution and track quality
- Multiple downloads

## Screenshots
### Python
![](https://github.com/yaronzz/Tidal-Media-Downloader/raw/master/Screenshots/tidal-dl.png)
### C#(gui)
![](https://github.com/yaronzz/Tidal-Media-Downloader/raw/master/Screenshots/tidal-gui-login.png)
![](https://github.com/yaronzz/Tidal-Media-Downloader/raw/master/Screenshots/tidal-gui-setting.png)
![](https://github.com/yaronzz/Tidal-Media-Downloader/raw/master/Screenshots/tidal-gui-info.png)
![](https://github.com/yaronzz/Tidal-Media-Downloader/raw/master/Screenshots/tidal-gui-dl.png)

## Libraries used

- [AIGS](https://github.com/yaronzz/AIGS)
- [Stylet](https://github.com/canton7/Stylet)
- [PropertyChanged.Fody](https://github.com/Fody/PropertyChanged)
- [MaterialDesignInXamlToolkit](https://github.com/ButchersBoy/MaterialDesignInXamlToolkit)

## Support

If you really like my projects and want to support me, you can star this project. 