# Segatools连接读卡器配置
将aimeio拷贝到amdaemon.exe所在目录，打开游戏文件夹中的segatools.ini，找到aimeio条目（如果没有可以自行在文件末尾手动添加），并按照如下方法配置
```ini
[aimeio]
path=SeikanIO_aimeio.dll
```
**aimeio文件可从本文档的Github Release中下载，请勿使用来源不明的DLL!!!**

适用于新固件的说明：新固件里加入了对AIC卡的access code直接读取，使用 AkariNEW+_Direct_On.exe 即可切换到直读模式
