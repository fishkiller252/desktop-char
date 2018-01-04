# デスクトップキャラクター

# お品書   
-  index.html    
-  main.js
-  icon.ico
-  icon.png
-  icon.icns
-  mac版パッケージ
-  Linux版パッケージ


## パッケージ化
electronとelectron-packagerが入っている前提です。

```  
# Windows
electron-packager . desktop-char --platform=win32 --electron-version=1.4.5 --icon=./icon.ico
# OSX
electron-packager . desktop-char --platform=darwin --electron-version=1.4.5 --icon=./icon.icns
# Linux
electron-packager . desktop-char --platform=linux --electron-version=1.4.5 --icon=./icon.png
```
