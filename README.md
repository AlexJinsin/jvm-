# jvm-
本文档用于描述如何查看jvm的堆栈信息以及查看线程数

1.jps 查看当前java所运行的所有进程的pid
2.jstack -l pid 查看当前线程情况
3.jmap -dump:format=b,file=/tmp/file.bin pid 导出当前堆栈信息
