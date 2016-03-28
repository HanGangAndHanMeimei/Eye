##perl语言入门
####第一章  简介

```
perl语言全称：实用摘录与报表语言|病态折中式垃圾列表器
perl语言历史：Larry Wall(拉里·沃尔)20世纪80年代中期
适合处理的任务：约有90%和文字处理有关，10%与其它事物有关的问题。
在MAC OSX系统上面默认已经自带提供了Perl编译器
第一个程序：输出hello Word wendingding!
	1)新建一个文本文件  如hello.pl
	2)在该文本文件中编写程序文本如下：
		#!usr/bin/perl
		print "Hello word Wendingding!\n";
	3)打开终端，进入到hello.pl文件路径
	4)执行终端命令授权：chmod u+x hello.pl
	5)编译和运行程序：perl hello.pl
	6)输入上面的指令后，命令行会输出hello Word wendingding!字样。
	
在OSX系统上面可以通过 perl -v指令来查看当前系统支持的perl版本，经测试发现是5.18.2
建议和鼓励适当使用缩排以增加程序的阅读性。
注释可以对代码的作用提供简单说明，注释为从#开始一直到行末尾的部分


```
#####2016 03 28 文顶顶