# Simple Note Windows desktop

After using the Simple Note on OSX for quite some time I wanted a desktop app of SimpleNote for Windows. So I created this. 

All it does is wrap the Simple Note website.

## Icon  
[Simple note, simplenote icon on Icon Finder](https://www.iconfinder.com/icons/386701/simple_note_simplenote_icon#size=128)

Icon provided with [Creative Commons (Attribution 3.0 Unported)](http://creativecommons.org/licenses/by/3.0/)

## Step by step guide
1. Install electron packager
```
npm install electron-packager -g
```
2. Run the packager in the directory as the project
```
electron-packager . SimpleNote --platform=win32 --arch=x64 --version=0.35.6 --icon=simplenote.ico
```
3. Relax and wait until your application is built

#### License [CC0 (Public Domain)](LICENSE.md)