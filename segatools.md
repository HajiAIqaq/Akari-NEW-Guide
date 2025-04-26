# Segatools连接读卡器配置
打开游戏文件夹中的segatools.ini,并按照如下方法配置
```ini
[aimeio]
; If you wish to sideload a different aimeio, specify the DLL path here
path=AkariNEW.dll
```
或者
```ini
[aimeio]
; To use a custom card reader IO DLL enter its path here.
; Leave empty if you want to use Segatools built-in keyboard input.
path=AkariNEW.dll
```
**aimeio文件可从本文档的Github Release中下载，请勿使用来源不明的DLL注入游戏!!!**