编写一个脚本，能够生成这样的脚本即：
编写shell脚本，该脚本接收两个参数，参数1作为要读写的文件，参数2作为标志位，标识是读还是写。
完成对参数1所示文件的读写
并且自动执行该生成的脚本
使用strace命令观察上面脚本的执行，并能够证明上述脚本在生成脚本时调用了系统调用write。
