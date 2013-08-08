unity3d-lzma-speedup-macos
==========================

Speedup unity3d web build compression on MacOS

For windows project please check this project [derFunk/unity3d-lzma-speedup](https://github.com/derFunk/unity3d-lzma-speedup)

this is a wrapper for lzma archiver which use unity

Shell script redirect parameters to original lzma, or you can switch on ```DEBUG``` mode and archiver will zip file with no compression

Usages
======
Installation
------
```bash
cd /Applications/Unity/Unity.app/Contents/Tools
mv lzma lzma.real
curl https://raw.github.com/nicloay/unity3d-lzma-speedup-macos/master/lzma >lzma
chmod a+x lzma
```

Temporary disable/enable
-------
go to the unity tools folder
```bash
cd /Applications/Unity/Unity.app/Contents/Tools
```
open lzma in your favorite text editor and comment this line ```DEBUG="ON"```
