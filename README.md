# dex_modify
分析dex文件，将指定函数指令置为nop

1.把dex文件放到工作目录下，名字固定为classes.dex，运行dex_main.py (为方便把所有函数移到一个文件里)

2.按提示输入类名，函数类型，函数名即可设置对应函数区指令为ROP.

注：这三项需直接复制smail文件中的命名方式，参照目录中的reference.png

3.为便于区分，输出的文件名以 (method)_rm.dex 格式命名
