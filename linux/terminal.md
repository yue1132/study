terminal使用小技巧：
	ctrl + a 光标移动到行首
	ctrl + e 光标移动到行尾
	ctrl + b 移动游标到上一个或当前单词的前面
	ctrl + k 删除当前游标到行为的文字
	ctrl + u 上出当前整行
	ctrl + w 删除游标前的单词
	ctrl + c 强制推出当前操作

ctrl + alt + F1 进入系统字符界面,ctrl + alt + F7 进入图形化界面
终端字符界面不支持中文的解决方式：
安装fbterm
sudo apt-get install fbterm
安装好后在字符界面输入sudo fbterm运行fbterm 替换系统自带的终端。系统字符乱码的问题及解决。



查看系统磁盘使用情况：
	df -h 查看哥哥文件系统当前的空间使用情况
	free -m 查看系统中使用和内存情况	
	top 查看linux系统的信息
	uname -a 查看系统的所有信息
	ls -sh 查看文件信息

系统用户管理:
	adduser newuser 创建一个用户名为newuser的新用户


终端打开应用程序：
	firefox &	加上&符号会使应用程序在后台运行，不会占用控制台。

条件执行语句：
	可以使用Bash运行两个命令，一个接着一个。第二个命令只有当第一个命令运行完毕后才会运行。要做到这样只需要在两个命令中使用“&&”分隔即可。
比如： “sleep”命令会以秒为单位接受一个参数。sleep 5 && gnome-screenshot
