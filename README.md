# run
把编译运行链接一起，使用一个命令
支持c/c++/java语言 可以添加运行参数
这个版本的必须要添加添加文件的后缀
eg:
有一个C语言文件名叫test.c
使用命令 run -c 1
Java与c++文件同理
注意 编译Java的时候使用的是gcj编译器，
这是GNU项目中的一个软件，用来把Java代码编译为二进制可执行代码，如果你的电脑中没有，请自行下载gcj
Debian系列下载使用命令

‘’‘
sudo ap-get install gcj

’‘’

Readhat系列使用yum下载 
另：该程序的c/c++编译器使用的是clang系列，可以在命令行自行下载，也可以更改本代码为gcc系列编译器

