# CZLibarclite-Files
解决Xcode升级14.3之后缺少libarclite_iphonesimulator.a文件的问题

终端 open /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/

如果lib文件夹不存在，在该文件夹中创建 “arc”的文件夹
