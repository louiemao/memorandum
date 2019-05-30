# Linux常用命令
- mv，移动一个文件
- cd，它用于切换当前目录
- mkdir，创建目录
- cp，复制一个文件
- cat，查看一个文件的内容
- head、tail，查看头几行或尾几行的内容
- more，按页来查看文件的内容
- scp，可以在 2个 linux 主机间复制文件
- pwd，在终端中显示当前工作目录的全路径
- ls，用于查看文件与目录
- grep，常用于分析一行的信息
- find，在目录中查找文件
- sed，主要用来自动编辑一个或多个文件
- awk，对文本和数据进行处理
- df，显示磁盘分区上的可使用的磁盘空间
- du，对文件和目录磁盘使用的空间的查看
- rm，删除文件或目录
- echo，创建带有内容的文件

# linux问题排查命令
- top, 实时显示系统中各个进程的资源占用状况
- vmstat，展现给定时间间隔的服务器的状态值
- sar，从多方面对系统的活动进行报告
- ps，查看当前进程
- Iostat，查看磁盘活动使用情况
- mpstat，查看CPU的一些信息
- free，显示系统使用和空闲的内存情况
- netstat，显示网络状态信息
- lsof，显示系统打开的文件
- ctrl+alt+F1  命令行全屏模式


# tail命令的使用
1. tail -f filename  
说明：监视filename文件的尾部内容（默认10行，相当于增加参数 -n 10），刷新显示在屏幕上。  
退出，按下CTRL+C。MAC control+Z
2. tail -n 20 filename  
说明：显示filename最后20行。
3. tail -r -n 10 filename  
说明：逆序显示filename最后10行。 

