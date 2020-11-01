# 目录

[TOC]



# 一、揭开操作系统的神秘面纱

## 1.1 什么是操作系统？

- 操作系统是用户和计算机的接口，同时也是计算机硬件和其他软件的接口；

- 用户程序是运行在操作系统之上的；

- 操作系统的功能包括管理计算机系统的硬件、软件及数据资源，控制程序运行，改善人机界面，为其他应用软件提供支持等，使计算机系统所有资源最大限度地发挥作用，提供了各种形式的用户界面，使程序有一个好的工作环境，为其他软件的开发提供必要的服务和相应的接口。

    ![image-20201101173700940](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173700940.png)

![image-20201101173722097](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173722097.png)

## 1.2 Linux的历史

![image-20201101173742538](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173742538.png)

**操作系统发展接触贡献者**

![image-20201101173801715](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173801715.png)

![image-20201101173826477](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173826477.png)

![image-20201101173856639](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173856639.png)

![image-20201101173912489](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173912489.png)

![image-20201101173929011](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173929011.png)



## 1.3 用户操作系统占比

![image-20201101173941638](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173941638.png)

## 1.4 服务器操作系统占比

![image-20201101173954355](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101173954355.png)

## 1.5 为什么要学习Linux

- 大厂必需，但学校未必学，被大众忽视
- 走进Linux的世界，你才能成为合格的软件工程师
- 研究Linux内核代码，将学到的数据结构和设计模式落地实践
- 了解Linux生态，能让你事半功倍的学习

## 1.6 需要Linux知识的岗位和技术

![image-20201101174008107](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174008107.png)

![image-20201101174050066](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174050066.png)

## 1.7 微软的发展

![image-20201101174100233](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174100233.png)

## 1.8 苹果的发展

![image-20201101174140841](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174140841.png)

## 1.9 微软与苹果

![image-20201101174215685](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174215685.png)

## 1.10 书籍

《鸟哥的Linux私房菜》

《Unix高级编程》

《Linux三件套》

# 二、由图形化转为字符界面

## 2.1 Windows与Linux的主要不同

![image-20201101174235684](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174235684.png)

此处说的Linux是没有图形化界面的，多指服务器。

## 2.2 命令格式

![image-20201101174303784](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174303784.png)

![image-20201101174330763](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174330763.png)

所有的命令都是命令的电脑，所以主语缺失。

比如`cat a.c`中`cat`就是谓语，`a.c`就是宾语。

而 `cat -n a.c`中就是 `-n`就是方式状语，以输出行号的方式读`a.c`文件。

Linux中以`.`开始的文件时隐藏文件，`ls -a` 或者 `ls --all`可以显示隐藏文件。

查找文件的位置：

```
whereis 命令
```

如果文件可执行，类似于`./a.out`中`.`表示当前，``/``是目录分隔符，`a.out`就是要执行的文件,这和`/bin/ls`本质上是一样的。`/bin/ls`表示的是执行根目录下的bin文件夹中的可执行文件ls。

**命令主体**对应的是系统中的可执行程序。

**不要忽略屏幕输出，请仔细看系统给你的每一句回复。**

![image-20200923110705107](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923110705107.png)

当前命令后面的数字表示上一条命令的执行结果，完整地执行成功返回结果是0，非0返回值可能是中途返回或者出现错误。

```
echo $?
```

可以获取上一条命令的返回值。

![image-20200923111115410](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923111115410.png)

有返回值的显示是因为在`.zshrc`中配置了`RPROMPT`:

```shell
RPROMPT="[%{$fg[yellow]%}%?%{$reset_color%}]"
```

## 	 2.3 用户与密码

![image-20201101174406563](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174406563.png)

查看用户的家目录，可使用

```shell
$HOME
```

![image-20200923111753234](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923111753234.png)

在home目录下直接创建文件是没有权限的：

![image-20200923122252900](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923122252900.png)

## 2.4 与用户相关的文件

![image-20201101174513732](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174513732.png)

/etc：全局配置目录，配置信息都是在该目录下。

**Linux下一切皆文件**

usermod:修改用户

userdel：删除用户

id：可以查看用户信息，省略宾语的时候默认是当前用户。

![image-20200923122740833](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923122740833.png)

## 2.5 用户与组

![image-20201101174538279](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174538279.png)

which：使用的是哪个

whereis：命令存在的所有位置，能查源码，帮助手册等。

![image-20200923124148181](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923124148181.png)

root用户具有rwx权限，而root组的用户具有rx权限，其他用户具有rx权限。

`sudo !!`给上一条命令加sudo权限。

![image-20200923124306820](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923124306820.png)

## 2.6 浏览文件

![image-20201101174608423](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174608423.png)

Linux中安装的软件中的不同部分如了执行程序、源码、帮助手册等放在不同的目录下。

## 2.7 拷问灵魂的三个问题

- 我是谁：当前的用户是谁 `whoami` `who am i`
- 我在哪：所在的路径`pwd(print working directory)`
- 我要去哪儿（资源在哪）：要查找的资源在哪儿(`wget`)

![image-20201101174742834](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174742834.png)

![image-20200923140922882](/Users/maureen/Library/Application Support/typora-user-images/image-20200923140922882.png)

![image-20200923141127280](/Users/maureen/Library/Application Support/typora-user-images/image-20200923141127280.png)

小技巧：`wget`命令输入之后可以按上下键，在之前执行过的`wget`命令中进行地址的切换。

### 2.7.1 相关命令及技巧

![image-20201101174800070](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174800070.png)

![image-20201101174854489](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174854489.png)

## 2.8 软件的安装

![image-20201101174906943](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174906943.png)

上图中提到的Linux下载一个压缩包xxx.tar也可以是下载xxx.zip。tar包使用tar解压；zip使用unzip解压。

apt是软件包管理工具，只针对于ubuntu系列；centos安装是使用yum。

### 2.8.1 与软件安装相关的命令

![image-20201101174920962](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174920962.png)

还有`apt install` 安装软件。

![image-20201101174931263](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174931263.png)

其中.deb是ubuntu系统，rpm是centos，tar.gz压缩包。

# 三、Linux常用命令

## 3.1 文件及目录相关命令

![image-20201101174944475](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174944475.png)

## 3.2 文件内容的修改与查看

![image-20201101174953145](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101174953145.png)

more只能往后看，less可以往回看。

wc：全称word count。

```shell
cat *.c | grep "lj"
```

`|`表示管道，管道是将前一个命令的输出，作为后一个命令的输入。

```shell
echo abc | ./a.out
```

`abc`经由管道被a.out读入，该命令的意思是将前一个命令的标准输出作为下一个命令的标准输入。

```shell
echo abc > 1.txt
```

`>`重定向到1.txt中，表示的数据的流向。

```shell
vim a
./a.out < a
```

`<` a文件的内容流向a.out中，即作为a.out的标准输入。

## 3.3 文件的查找与定位

![image-20201101175004026](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101175004026.png)

`locate`是通过索引查找文件，但是所以可能更新不及时，所以要先通过`updatedb`命令更新数据库，然后再使用`locate`定位文件。

## 3.4 用户相关命令

![image-20201101175012580](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201101175012580.png)

**`chmod`用法：**

1、`chmod a+x index.html`表示给所有人加上`index.html`的可执行权限。

![image-20200923173540677](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923173540677.png)

2、`chmod a-x index.html` 移除可执行权限

3、`chmod a=x index.hltml`使得所有用户都只有可执行权限

4、`a`表示all，还有其他选项参数：

![image-20200923173845327](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923173845327.png)

**`chown`用法：**

1、修改文件所属的用户和组，用法：

```shell
chown user:group filename
```

`group`表示用户`user`所属的组。

2、修改文件所属的用户

```shell
chown user filename
```

**`chgrp`用法：**

1、修改文件所属的组

```shell
chgrp groupname filename
```

## 3.5 进程相关命令

![img](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/96390697582a98e440147a906a42f67aa08903fb.png)

**`ps`用法**

1、查看系统当前运行的进程

```shell
ps -ef
```

## 3.6 系统信息获取命令

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/95e8d826bc88b6529919a5c33cc0fcfe00e34be3.png" alt="img" style="zoom:50%;" />

`free`查看内存用了多少，剩了多少。

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923175051740.png" alt="image-20200923175051740" style="zoom:50%;" />

`dstat`可以查看CPU是否忙、磁盘是否忙、网络传输数据是否多

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923175317959.png" alt="image-20200923175317959" style="zoom:50%;" />

## 3.7 其他命令

![img](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/482024683b8879c1c60fac565845780c1ddb275d.png)

TTY：虚拟终端。

![image-20200923232452070](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200923232452070.png)

1和0都是字符设备，是个流，流过就没有了。所以这里用`echo abc >> 1`和`echo abc > 1`的效果是一样的。`>>`是追加，`>`是覆盖。



# 四、基础知识

## 4.1 Terminal

**终端**（`termimal`）= `tty`（Teletypewriter， 电传打印机），作用是提供一个命令的输入输出环境，在linux操作系统下使用组合键`ctrl + alt + T`打开的就是终端，可以认为`terminal`和`tty`是同义词。

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200924143615080.png" alt="image-20200924143615080" style="zoom:50%;" />

## 4.2 Shell

`shell`是一种人机交互的接口。`shell`有壳的意思，是指***“提供使用者使用界面”*** 的软件，是一种命令解析器,是Linux内核的一个壳，负责外界与Linux内核的交互。

>windows 的cmd就是一种shell。所以**``shell``并不只是指命令语言**。
>
>其实GUI本身也是一种shell。

用户在`shell`中提交命令，`shell`负责接收用户的命令，并扮演命令解析器的角色。

当你打开一个`Terminal`时，操作系统会将`Terminal`和`Shell`关联起来，当我们在`Terminal`中输入命令的时候，`Shell`就负责解释命令。

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200924143700090.png" alt="image-20200924143700090" style="zoom: 67%;" />

![image-20200924143743035](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200924143743035.png)

`built-in`就表示内置。

### PATH变量

`PATH`变量是用来存放系统中所有可执行文件的路径。

如果可执行文件不在PATH目录中，就需要指明可执行文件的路径，否则是不能运行的。

如果想让执行程序在任何地方都能运行的话，有如下两种方式：

1. 将可执行文件复制到`/usr/bin`目录下。

2. 将可执行文件所在的目录添加到PATH变量中：

   ```SHELL
   PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:添加新的可执行文件所在路径
   ```

   如果有不同版本的可执行文件，想让更新的版本生效，可以将其所在路径配到`PATH`变量中更靠前的位置。

每个终端都是开启了一个进程，在该终端中执行的命令都是在内存中的，如果不将其保存到硬盘中，那么当该终端终止也就是进程结束的时候，命令的执行结果也会消失。

**问**：**<u>如何将`PATH`变量写到磁盘中？</u>**

**答**：将`PATH`变量写到`.zshrc`文件中，`.zshrc`是资源文件，每次打开`zsh`的时候就会执行一遍，这就相当于将`PATH`写到了磁盘中(固化）。所有想要写到磁盘中的信息都要写到配置文件中才会固化。

## 4.3 命令

>命令是人和计算机交互的基本单位，人使用*命令*将要做什么事传达给计算机，计算机做出解析，并做出回应。

**命令也有自己的语法结构：**

`和人说话一样，命令的主要结构也可以看做为主谓宾的简单句和复杂句，在命令中，省略主语`

>举个例子

```sh
cp(谓语动词)  fileA(宾语)  fileB(宾语)
```

```sh
cp(谓语动词)  -ar(方式状语)  fileA(宾语)  fileB(宾语)
```

>一般情况下`-`后面加选项的缩写，`--`后面加选项的全称。

### 4.3.1 命令细节

> Linux命令由以下几个部分组成：**命令名**，**分隔符**，**选项**和**操作对象**组成。

#### 4.3.1.1 命令名

命令名标识了命令的功能，如cp，rm，mv，rename，fdisk等等，都能很轻易的看出该命令的功能，还有一些命令，有二级子命令，如apt-get install | remove，install和remove就是apt-get的子命令。

#### 4.3.1.2 分隔符

分隔符通常为空格，连续的多个空格会被视为一个空格。

> 一些特殊的符号也属于分隔符，例如管道**|**，重定向**>**, **<<** , **<**, **>>**，后台运行**&**，序列执行**&&**、**;**都是特殊的分隔符，在使用这些特殊符号的时候，不需要额外加空格，但为了使命令更易读，通常会加上空格。

#### 4.3.1.3 选项

* 命令的选项通常用**`-`**连接，通常为一个字母，是选项的首字母。大多数命令都可以使用**`-h`**来查看该命令的帮助。
* 命令的选项也可以使用**`--`**来引导，接的是选项的全称，效果与`-`连接单个字母是一样的。

#### 4.3.1.4 操作对象

操作对象为该命令动作的承受者。

### 4.3.2 格式约定

* 使用**`[]`**来标记可以选择的选项
* 使用**`|`**来表示不能同时使用的参数
* 选项通常紧跟命令名，当然，在很多时候我们可以省略命令的选项而使用默认参数

### 4.3.3 答疑

#### 4.3.3.1 `su - user`中`-`的作用

```shell
su - lj
```

其中的`-`是使得用户重新登录，当前状态下的环境变量都会失效，而切换到新用户的环境变量，重新登录后已经回到了根目录`~`。

如果不加`-`，那么用户虽然重新登录了，但是当前环境变量还是保留着，最明显的可以看到重新登录后还在当前目录。

![image-20200924151434856](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200924151434856.png)

#### 4.3.3.2 `sudo`和`su`的区别

`su`只能用来切换用户

`sudo`用来临时获取管理员权限，但是有个特殊用法：`sudo -i`可以在使用当前用户的密码下回到root用户。



## 4.4 程序与进程

>我们执行命令的时候，每一个命令，其实对应的就是系统中的一个程序。
>下图使用`which`命令查找`cp`命令的位置，并使用`ll`和`file`命令查看`cp`命令的具体信息：

![](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/F46DCEF8005D4575850B31B167453846.jpg)
通过`ll`和`file`命令可以看出文件cp是一个可执行的二进制文件，也就是我们平时所说的程序。

>那么什么是程序呢？
>
>>计算机程序是指一组指示计算机执行动作或做出判断的指令，通常用某种程序设计语言编写，运行于某种目标体系结构上。




>什么又是进程呢？
>
>>进程是程序在内存中的镜像。

## 4.5 路径

### 4.5.1 绝对路径

绝对路径的起始点为根目录`/`,例如`/usr/bin/cp`就是一个绝对路径。

### 4.5.2 相对路径

相对路径的起始点为当前路径`.`，假如用户当前目录为`/home/suyelu/`，那么同样的文件`cp`,其相对路径为`../../usr/bin/cp`。

>相对路径和绝对路径在使用上各有差异，在使用时需要考虑实际的情况选择。

### 4.5.3 远程路径

>在很多时候，我们会需要访问本机之外的资源，这个时候远程路径就有了用武之地了。

远程路径的一般表示方法为：```协议://用户名:密码@位置/路径:端口```，并不是每个路径都需要这些参数。
比如：

```http://haizeix.com```

```ftp://user:passwd@ftp.haizeix.com:21```

远程路径根据应用的不同，具体表示方法和所需要的参数都不太一致，从以上两个远程路径就可以看出。

### 4.5.4 路径相关的命令

>`cd` #**c**hange **d**irectory

>`ls`  #**l**i**s**t
>
>`pwd`  #**p**rint **w**orking **d**irectory

### 4.5.5 特殊路径

* `~` ：家目录
* `-` ：`cd -`是回到之前所在的目录

![image-20200927151257508](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927151257508.png)

![image-20200927151329486](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927151329486.png)

- `~username`: `cd ~username`是回到username用户的家目录

## 4.6 软件

在Linux中，软件并没有像注册表这样的概念。

>*注册表：是Microsoft Windows中的一个重要的数据库，用于存储系统和应用程序的设置信息。*
>安装软件。理论上只需要拷贝相关文件，并执行其主程序就可以。

通常，一个软件包含的内容会分别被拷贝到同级别的`bin` `lib` `share` 和 `/etc`目录下。

>**bin**  存放程序的可执行文件。在系统环境变量中将该路径添加进去，就可以直接执行程序.
>
>**lib**  库文件集中存放，方便共享。
>
>**share** 存放程序需要的其他资源，如man手册，源码等。
>
>**/etc** 配置文件存放路径，大部分的程序的配置文件都可以在这个路径下找到。



## 4.7  配置方式

在Linux中，所有的配置操作都可以使用纯文本的配置文件来配置，为了方便使用，有很多程序都会提供命令接口供用户更加便捷来个性化的配置自己的系统。

在Linux中做网络配置，即可以通过修改配置文件的方式来配置，可以直接使用命令来配置：
<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927152322318.png" alt="image-20200927152322318" style="zoom:67%;" />

>`/etc/network/interface`文件为Ubuntu的网络配置文件，通过修改该文件，并重启网络，就可以实现网络的配置工作。

当然也可以直接使用ifconfig命令来直接修改网络配置：

```powershell
ifconfig eth0 172.17.211.175
```

这条命令将把设备`eth0`的ip地址更新为`172.17.211.175`，但是这种方式也只是临时修改，重启是不会生效的，所以通常使用功能的方法都是修改interface文件。

>对于interfaces文件中的其他所有配置，都可以使用命令来修改，在这里不一一举例，在后期的学习中，我们会学到它们的用法。

## 4.8 隐藏文件

>在Linux也有隐藏文件，与Windows不同的是，如果我们想查看隐藏文件不需要去文件夹选项中修改配置，让系统在显示文件的时候显示被隐藏的文件或者文件夹。

Linux的隐藏文件都是以`.`开头的，也就是说所有以`.`开头的文件都会被系统识别为隐藏文件。
![](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/61434A0C5C884598A00EA3B7AEBD6D39.jpg)
如图，使用`ls` 命令添加`a`选项，就可以显示隐藏文件。

这里有两个特殊的目录`.`和`..`,分别为当前目录和父目录。

>如何在显示隐藏文件的时候，不显示`.`和`..`呢？自己尝试一下吧！
>
>答：使用`ls -A`命令即可不显示`.`和`..`，man手册中提到了该命令的参数-A的用法：
>
>![image-20200927232853228](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927232853228.png)

## 4.9 文件类型

使用`ll`命令可以查看当前文件夹下所有文件的详细信息。

>`ll` 等效于  `ls -al`
>
>`ll` 是 `ls -lh`的别名，h表示head，human等。

```bash
suyelu@HaiZei-Tech:~$ ll
total 52
drwxr-xr-x 5 suyelu suyelu 4096 Apr 27 11:40 ./
drwxr-xr-x 3 root   root   4096 Apr 23 13:40 ../
-rw------- 1 suyelu suyelu 2064 Apr 27 11:49 .bash_history
-rw-r--r-- 1 suyelu suyelu  220 Apr 23 13:40 .bash_logout
-rw-r--r-- 1 suyelu suyelu 3486 Apr 23 13:40 .bashrc
drwx------ 2 suyelu suyelu 4096 Apr 23 17:25 .cache/
drwxrwxr-x 3 suyelu suyelu 4096 Apr 23 18:07 code/
-rw-r--r-- 1 suyelu suyelu 4096 Apr 23 18:06 ._.DS_Store
-rw-r--r-- 1 suyelu suyelu 6148 Apr 23 18:43 .DS_Store
-rw-r--r-- 1 suyelu suyelu  675 Apr 23 13:40 .profile
drwxrwxr-x 2 suyelu suyelu 4096 Apr 26 21:32 .ssh/
-rw------- 1 suyelu suyelu 1876 Apr 27 11:40 .viminfo
```

该命令主要输出了七列内容，分别为：**权限、文件数、所属用户、所属群组、文件大小、常见日期（修改时间)、文件名**。

第一列权限，主要可以分为以下四个部分：文件类型，所属用户权限，所属组权限，其他用户权限。

>以刚才执行ll的结果中的`../`目录的权限为例：
>
>| 文件类型 | 所属用户权限 | 所属群组权限 | 其他用户权限 |
>| :------: | :----------: | :----------: | :----------: |
>|    d     |     rwx      |     r-x      |     r-x      |

* 第一部分文件类型为`d`,代表这个文件是一个目录(**d**irectory)，目录是一种特殊的文件；
* 第二部分所属用户权限为`rwx`，代表该文件拥有者拥有可读(**r**ead),可写(**w**rite),可执行(e**x**ecute)的权限；
* 第三部分所属群组权限为`r-x`，代表与该文件拥有者在一个群组的用户具有可读，可执行的权限，在这里`-`顶替了`w`的位置，代表没有写权限；
* 第四部分其他用户权限同样为可读，可执行。

>***需要注意的是`rwx`的顺序是固定的！***

Linux中的文件类型除了目录`d`之外，总共有7种文件类型，在这里我们做一个简要的了解：

* `-` regular file  普通文件
* `d` **d**irectory 目录
* `l` **l**ink 链接
* `b` **b**lock  块设备 存储数据以供系统存取的接口设备，也就是硬盘
* `c` **c**haracter  字符设备 串口设备，键盘，鼠标等
* `s` **s**ocket套接字
* `p` **p**ipe 管道，别名是fifo

### 4.9.1 普通文件

对于普通文件又可以分为以下三种：

* 纯文本文件

纯文本文件使用ASCII编码，这是Linux系统中最常见的一种文件类型，之所以成为纯文本文件，是因为这种类型的文件是我们可以直接读取的内容，在Linux，几乎所有的配置文件都属于这种类型。

* 二进制文件

二进制文件是系统中的可执行文件(不包括脚本)，计算机只能认识并执行二进制文件。二进制文件不能使用`cat`等命令直接读出。

* 数据格式的文件

在一些程序运行过程中，需要读取特定格式的文件，这种文件被称为数据文件(data file)。这种文件通常也不能使用cat命令读出。
例如：`/var/log/wtmp`文件。
<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927160203378.png" alt="image-20200927160203378" style="zoom:67%;" />

使用`ll`命令查看文件，可以看到该文件为普通文件

```sh
suyelu@HaiZei-Tech:~$ ll /var/log/wtmp
-rw-rw-r-- 1 root utmp 8832 Apr 27 11:50 /var/log/wtmp
```

使用file命令查看文件详情，返回为`data`

```sh
suyelu@HaiZei-Tech:~$ file /var/log/wtmp
/var/log/wtmp: data
```

使用cat命令读取该文件为乱码，但是使用`last`命令则可以读取该文件中的内容。

```sh
lj@Aliyun ~ % last -f /var/log/wtmp                                                                                                                                                       
root     pts/0        113.87.183.42    Sun Sep 27 15:49   still logged in
root     pts/0        113.87.183.42    Sun Sep 27 15:11 - 15:47  (00:36)
root     pts/0        116.25.147.241   Fri Sep 25 18:09 - 20:05  (01:56)
root     pts/0        116.25.147.241   Thu Sep 24 13:06 - 16:35  (03:28)
root     pts/0        113.118.186.166  Thu Sep 24 01:34 - 01:47  (00:13)
root     pts/1        113.118.186.166  Wed Sep 23 23:11 - 23:54  (00:42)
```

last命令表示最近登录的次数。

**需求1：使用linux命令查看最近有多少用户登录，每个用户登录了多少次，以次数递减方式显示结果？**

```sh
last | grep -v ^$ | grep -v begins | cut -d " " -f 1 | sort | uniq -c | sort -r
```

![image-20200927161645880](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927161645880.png)

`grep -v ^$` 删除last结果中的空行，-v反向查找，即不包含什么字符的结果

`grep -v begins` 删除last结果中的最后一行

`cut -d " " -f 1`：对每行结果遇到空格时切割，并选取切割后的第一块

`sort`：对结果进行排序，递增

`uniq -c`：归一化，对每个用户进行计数操作

`sort -r`：递减排序



### 4.9.2 连接文件

软连接：`ln -s a.c b.c`

![image-20200927163059513](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927163059513.png)                                                                                                                                                              

可以看到，将a.c链接到b.c，访问b.c实际是访问的a.c，但是b.c的大小远小于a.c的大小。修改b.c，a.c也会被修改。

硬连接：`ln a.c c.c`

![image-20200927163008838](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927163008838.png)                                                                                                                                                                      

c.c和a.c完全相同，相当于一个文件有了两个名字。

`ls -ali`：i 表示inode，该命令可以查看文件结点。

![image-20200927163237743](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927163237743.png)

可以看到文件结点完全相同。如果修改c.c，那么a.c也会被修改。

### 4.9.3 块设备

vda：virtual disk 第一个

vda1：虚拟磁盘的第一个分区



### 4.9.4 管道文件

新建一个管道文件a:

![image-20200927164044750](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927164044750.png)

### 4.9.5 文件权限

> 在上节我们已经提到了文件的权限包含三组(`u`用户，`g`群组，`o`其他用户)，每一组又都包含三组具体的权限(`r`读，`w`写，`x`执行)。

对于文件权限，我们也可以用下面的方式来表示：

|     r      |     w      |     x      |     r      |     w      |     x      |     r      |     w      |     x      |
| :--------: | :--------: | :--------: | :--------: | :--------: | :--------: | :--------: | :--------: | :--------: |
| (2^2)**4** | (2^1)**2** | (2^0)**1** | (2^2)**4** | (2^1)**2** | (2^0)**1** | (2^2)**4** | (2^1)**2** | (2^0)**1** |

也就是权限的每一组都由三个十进制的数字表示，该组的的权限就可以简单的用着三个十进制的数字相加得到。

> 一个权限为`rwxr-xr-x`的文件，则它的权限可以使用`755`来表示。

### 4.9.6 与文件权限有关的命令

```sh
chmod #更改文件权限
chown #更改文件所属用户
chgrp #更改文件所属组
```

* `chmod`的用法

```shell
chmod a+x file #给file文件的ugo都赋予执行的权限
chmod o-x file #将file文件o减去执行权限
chmod 755 file #设置file文件的权限为rwxr-xr-x
chmod u=rwx,go=rx file #设置file文件的权限为rwxr-xr-x
```

* `chown`的用法

```shell
chown suyelu:haizei file #修改file的所属用户是suyelu,所属组为haizei
chown -R suyelu:haizei directory #修改目录directory及目录下的所有文件的所属用户是suyelu，所属组为haizei， -R是递归
chown suyelu file #修改file的所属用户为suyelu
```

* `chgrp`的用法

```shell
chgrp root file #修改file所属的组为root
```

更加详细的用法在后续继续学习！

### 4.9.7 补充：`<<`符号的作用

`<<` 定义分隔符。

![image-20200927154114616](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927154114616.png)

cat从标准输入读内容，读到EOF就结束。

## 4.10 用户

>Linux有两类用户,分别是`root`和`普通用户`。

* 超级管理员：`root`

`root`拥有系统的完全控制权，所以在使用Linux系统的时候，需要慎重使用root用户，更多的自由与权限同样也意味着更大的风险。

> 实际上，有很多Linux系统在默认情况下是不开放root用户的，这是出于安全方面的考虑。

* 普通用户

普通用户拥有的权限就没有`root`用户那么大了，它只能做系统允许做的事。普通用户可以执行大部分的命令，但是root专有的命令却不能执行。

```shell
suyelu@HaiZei-Tech:~$ reboot
reboot: Need to be root
```

> 后续的学习中，我们也会学习如何让普通用户拥有root的权限。

在使用过程中，可以使用`su`命令来切换用户。

```sh
suyelu@HaiZei-Tech:~$ whoami
suyelu
suyelu@HaiZei-Tech:~$ su - root
Password:
root@HaiZei-Tech:~# whoami
root
root@HaiZei-Tech:~# su - suyelu
suyelu@HaiZei-Tech:~$ whoami
suyelu
```

> ` su - root`这里的`-`代表什么意思？

表示不保留当前的环境变量。

# 五、命令系统

## 5.1、shell、terminal和console

上一章节中我们已经学习过什么是shell，shell是一种命令解析器，它给用户提供了一个输入命令并接受机器返回结果的界面。

那么什么是`terminal`和`console`呢？

>**console：**The operator's station of a mainframe.

> **terminal**：<hardware> An electronic or electromechanical device for entering data  into a computer or a communications system and displaying data received.  Early  terminals were called  teletypes, later ones VDUs.



![](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/584E6502CDF64D059CE7EE04F808945B.jpg)

上图所示的就是console（控制台），一般console只能有一个（显示器或电脑用串口线连接）。

![](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/DF08DD583D5F47EC9C34B9B575E14B9A.jpg)

上图是terminal的示意图，它是一个封装程序，一个terminal运行一个shell来扩充为一个具备shell功能的的程序。

> console 和 terminal的概念都源自大型机，console可以看作为一个特殊的terminal。现在用的一般都是引申义，一般情况下可以混用。

根据terminal的示意图，重定向不同类型的输出文件：

`1>` ：或者`>` 表示标准输出重定向

`2>`：标准错误重定向

将标准输出和标准错误输出重定向到同一个文件：

![image-20200927212556622](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927212556622.png)

`2>&1`表示将标准错误输出重定向到标准输出中，此处即`ls.log`

![image-20200927222052253](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927222052253.png)

`./a.out < a`和`./a.out 0<a` 是等价的，因为0表示的标准输入文件。

### write error: broken pipe错误

针对如下的a.c程序，无标准输入的操作时：

![image-20200927221517121](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927221517121.png)

遇到了错误：

```sh
echo: write error: broken pipe
```

该错误的原因是：参考自[Linux编程问题—broken](https://blog.csdn.net/u010419967/article/details/24236873)

​	1）broken pipe的字面意思是“管道破裂”。broken pip的原因是该管道的读端被关闭。上面的代码中并没有标准输入，即读端被关闭。

​	2）broken pipe经常发生socket关闭之后（或者其他的描述符关闭之后）的write操作中。

​	3）发生broken pipe错误时，进程收到SIGPIPE信号，默认动作是进程终止。

​	4）broken pipe最直接的意思是：写入端出现的时候，另一端却休息或退出了，因此造成没有及时取走管道中的数据，从而系统异常退出。

## 5.2、Linux帮助系统

> 在学习使用Linux的时候，我们会遇到很多以前没有用过的命令和功能，这个时候最好的解决办法就是求助于**man**.

`man`的使用方法很简单，例如查看`ls`的帮助手册，可以直接使用命令`man ls`即可查看`ls`的命令帮助。

```sh
LS(1)                                       User Commands                                LS(1)



NAME  #命令全名，简单的说明及用法
       ls - list directory contents

SYNOPSIS #基本语法
       ls [OPTION]... [FILE]...

DESCRIPTION #详细说明语法中参数的用法
       List information about the FILEs (the current directory by default).  Sort entries alphabeti‐
       cally if none of -cftuvSUX nor --sort is specified.

       Mandatory arguments to long options are mandatory for short options too.

       -a, --all
              do not ignore entries starting with .

       -A, --almost-all
              do not list implied . and ..

       --author
              with -l, print the author of each file
 #中间省略
       -1     list one file per line

       --help display this help and exit

       --version
              output version information and exit

       SIZE  may be (or may be an integer optionally followed by) one of following: KB 1000, K 1024,
       MB 1000*1000, M 1024*1024, and so on for G, T, P, E, Z, Y.

       Using color to distinguish file types is disabled both by  default  and  with  --color=never.
       With --color=auto, ls emits color codes only when standard output is connected to a terminal.
       The LS_COLORS environment variable can change the settings.  Use the dircolors command to set
       it.

   Exit status: #错误返回值
       0      if OK,

       1      if minor problems (e.g., cannot access subdirectory),

       2      if serious trouble (e.g., cannot access command-line argument).

AUTHOR  #作者
       Written by Richard M. Stallman and David MacKenzie.

REPORTING BUGS #bug提交联系方式
       Report ls bugs to bug-coreutils@gnu.org
       GNU coreutils home page: <http://www.gnu.org/software/coreutils/>
       General help using GNU software: <http://www.gnu.org/gethelp/>
       Report ls translation bugs to <http://translationproject.org/team/>

COPYRIGHT  #版权保护
       Copyright  ©  2011 Free Software Foundation, Inc.  License GPLv3+: GNU GPL version 3 or later
       <http://gnu.org/licenses/gpl.html>.
       This is free software: you are free to change and redistribute it.  There is NO WARRANTY,  to
       the extent permitted by law.

SEE ALSO ##在哪里可以看到更多关于该命令的文档
       The full documentation for ls is maintained as a Texinfo manual.  If the info and ls programs
       are properly installed at your site, the command

              info coreutils 'ls invocation'

       should give you access to the complete manual.



GNU coreutils 8.12.197-032bb               September 2011                                      LS(1)
```

> 眼尖的同学应该注意到了手册中开头和结尾的地方写的`LS(1)`了，那么这是什么意思呢？它代表的是一般用户可使用的命令。

在man中，常见的几个数字的含义如下表所示：

| 代号 | 代表的含义                                  | 举例               |
| :--: | :------------------------------------------ | ------------------ |
|  1   | 用户在shell环境下可以操作的命令或可执行文件 | `man 1 ls`         |
|  2   | 系统内核可调用的函数和工具                  | `man 2 reboot`     |
|  3   | 一些常用的函数与函数库，大部分C的函数库     | `man 3 readdir`    |
|  4   | 设备文件的说明，通常是在`/dev`下的设备      | `man 4 null`       |
|  5   | 配置文件或某些文件的格式                    | `man 5 interfaces` |
|  6   | 游戏                                        | `man 6 lol` 😂      |
|  7   | 惯例与协议等，例如Linux文件系统，网络协议等 | `man 7 tcp`        |
|  8   | 系统管理员可用的命令                        | `man 8 reboot`     |
|  9   | 跟kernel有关的文件                          |                    |
|  o   | 旧文档                                      |                    |
|  n   | 新文档                                      |                    |
|  l   | 本地文档                                    |                    |

可以通过`ls man?/`命令查看对应section的man手册中包含的所有可查看的内容。

比如：`ls man6/`枚举了man6手册中包含的所有游戏。

![image-20200927235404457](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927235404457.png)

在man手册中，我们可以用到的快捷键如下：

| 快捷键          | 功能                 | 快捷键      | 功能                 |
| --------------- | -------------------- | ----------- | -------------------- |
| Ctrl+f(orward)  | 向下翻一页           | Ctrl+d(own) | 向下翻半页           |
| Ctrl+b(ackward) | 向上翻一页           | Ctrl+u(p)   | 向上翻半页           |
| /               | 查找                 | q(uit)      | 退出                 |
| n               | 跳到搜索结果的下一个 | N           | 跳到搜索结果的上一个 |

随堂练习：

```shell
man -f            #whatis，查找对应的内容，全匹配
man -k            #apropos，通过关键字查找，包含该关键字的结果
```

![image-20200927235502438](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200927235502438.png)

> 在Linux中还有一种在线求助的方式`info`,有兴趣的可以了解一下。



<span style="font-size:25px">**tldr**</span>：全称`too long don't read`，显示最常用的命令。

```sh
#tldr的安装
sudo apt install tldr
```

![image-20200928000042634](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928000042634.png)

`{{}}`表示内容根据实际情况修改。

## 5.3、bash

### 5.3.1 通配符

* ？

    代表**单个任意字符**

* *

    代表**任意几个任意字符**

> 请看下面的例子，并自己动手尝试一下通配符的使用

```bash
suyelu@HaiZei-Tech:~$ ls
a.log  code  HaiZei  helloworld  你好world
suyelu@HaiZei-Tech:~$ ls *ld
helloworld  你好world
suyelu@HaiZei-Tech:~$ ls ??world
你好world
suyelu@HaiZei-Tech:~$ ls ?????world
helloworld
suyelu@HaiZei-Tech:~$
```

除了*****和**?**这两个通配符之外，Linux中还有下面几种通配符

| 通配符                | 含义                                      | 举例                                                         |
| --------------------- | ----------------------------------------- | ------------------------------------------------------------ |
| [list]                | 匹配list中的任意单一字符                  | a[xyz]b  a与b之间有且只有一个字符, 且只能是x或y或z, 如: axb, ayb, azb。 |
| [!list]               | 匹配除list中的任意单一字符                | a[!0-9]b  a与b之间有且只有一个字符, 但不能是数字, 如axb, aab, a-b等，这是bash的用法。如果是zsh，则是`a[^b]a`这种写法，表示第二个字符串包含b的。 |
| [c1-c2]               | 匹配c1-c2中的任意单一字符                 | a[0-9]b  a与b之间有且只有一个字符，该字符是0-9之间的数字，如a0b, a1b，... ，a9b。 |
| {string1,string2,...} | 匹配 sring1 或 string2 (或更多)其一字符串 | a{abc,xyz,123}b    a与b之间只能是abc或xyz或123这三个字符串之一。 |

通配符的说明：`man 7 glob`

![image-20200928145844856](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928145844856.png)

### 5.3.2 任务管理

1. **`&`**

    在命令的后面加上**`&`**表示后台执行的意思

    ```shell
    command &
    ```

2. **`;`**

    在命令之间以**`;`**相连，表示顺序执行的意思

    ```shell
    command1;command2
    ```

3. **`&&`**

    命令之间以**`&&`**相连时，只有第一个命令成功执行，第二个命令才会执行

    ```shell
    command1 && command2
    ```

4. **`||`**

    命令之间以**`||`**相连时，如果前一个命令执行失败，则执行第二个命令

    ```shell
    command1 || command2
    ```

5. **` `` `**

    命令替换符，相当于$()，符号**``** 的结果作为父命令的参数。命令中如果包含另一个命令，则用符号**``** 将它包括起来，在执行的时候系统将优先执行**``**中的子命令，然后将其结果代入父命令继续执行

    ```shell
    command1 `command2`
    ```

6. **`ctrl + z`**

    在shell中执行命令时，同时按下**`ctrl + z`**可以将暂时挂起


```shell
suyelu@HaiZei-Tech:~$ vim helloworld.c

[1]+  Stopped                 vim helloworld.c
suyelu@HaiZei-Tech:~$
```

 >什么是挂起？
 >
 >保存现场，切出内存，放到外存中。


7. **`bg`**

    执行**`bg`**命令，可以将挂起的命令后台运行

```shell
suyelu@HaiZei-Tech:~$ vim helloworld.c


[1]+  Stopped                 vim helloworld.c
suyelu@HaiZei-Tech:~$ bg
[1]+ vim helloworld.c &
suyelu@HaiZei-Tech:~$
```

8. **`fg`**

    执行命令**`fg`**可以将后台执行的命令转为前台执行，相当于%

9. **`jobs`**

    在Linux系统中，执行**`jobs`**命令可以查看所有在后台执行和挂起的任务以及任务编号

```shell
suyelu@HaiZei-Tech:~/code$ jobs
[1]-  Stopped                 vim a.c  (wd: ~)
[2]+  Stopped                 vim b.c  (wd: ~)
[3]   Running                 ./a.out &
```

> 尝试执行**fg**和**bg**加上任务编号，看看是什么效果

10.**`ctrl + c`**

​	shell执行命令时，按`ctrl + c`可以结束任务。但是对于后台运行的命令是无效的，如果想`ctrl + c`结束后台命令，需要把后台运行的任务转为前台，然后按`ctrl + c`。

11. **`kill`**

    使用kill命令杀死任务，需要知道任务的进程号。先使用`ps -ef | grep xxx`找到要杀死的任务的进程号，然后使用`kill pid`杀死任务。

12. **`pkill`**

    批量杀进程，`pkill 进程名`，容易误杀。

13. **`%`**

    将任务切到前台，如果只是`%`，则是将最近挂起的任务切到前台；多个任务挂起的是偶，使用`%num`（num为任务编号）将指定任务切到前台

### 5.3.3 管道、重定向

1. `>`

    重定向符

2. `>>`

    作用于**>**基本相同，不同的是**>>**将内容追加到文件的末尾，而**>**内容覆盖原文件

3. `<`

    与**>**刚好相反，是从文件到命令的重定向。它将文件的内容输出到命令作为输入

4. `<<`

    ?

```sh
# 在/etc/sysconfig/network文件中追加一行HOSTNAME=$HOST_NAME
cat >> /etc/sysconfig/network << EOF
HOSTNAME=$HOST_NAME
EOF 
```

过程分解：cat读取标准输入中以EOF结束的内容，读完之后会打印出来，将打印出来的内容追加到/etc/sysconfig/network中。

**`|`** ：管道，前一个命令的结果作为后一个命令的标准输入。

### 5.3.4 转义符

> 在Linux中转义符**`\`**的应用十分广泛，除此之外，转义符还包括**“”**和**‘’**。

| 字符 | 说明                                                         |
| ---- | ------------------------------------------------------------ |
| ''   | 硬转义,硬引用，其内部所有的shell元字符、通配符都会被关掉。注意，硬转义中不允许出现’(单引号)。 |
| ""   | 软转义，软引用，其内部只允许出现特定的shell元字符($,\`,\\)：$用于变量值替换、`用于命令替换、\用于转义单个字符 |
| \    | 反斜杠，转义，去除其后紧跟的元字符或通配符的特殊意义。       |

![image-20200928152750237](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928152750237.png)

下表是部分转义字符对应表：

| 转义字符 | 意义                                | ASCII码值（十进制） |
| -------- | ----------------------------------- | ------------------- |
| \a       | 响铃(BEL)                           | 007                 |
| \b       | 退格(BS) ，将当前位置移到前一列     | 008                 |
| \f       | 换页(FF)，将当前位置移到下页开头    | 012                 |
| \n       | 换行(LF) ，将当前位置移到下一行开头 | 010                 |
| \r       | 回车(CR) ，将当前位置移到本行开头   | 013                 |
| \t       | 水平制表(HT) （跳到下一个TAB位置）  | 009                 |
| \v       | 垂直制表(VT)                        | 011                 |
| \\\      | 代表一个反斜线字符''\'              | 092                 |
| \'       | 代表一个单引号（撇号）字符          | 039                 |
| \"       | 代表一个双引号字符                  | 034                 |
| \?       | 代表一个问号                        | 063                 |
| \0       | 空字符(NULL)                        | 000                 |
| \nnn     | 1到3位八进制数所代表的任意字符      | 三位八进制          |
| \xnnn    | 1到3位十六进制所代表的任意字符      | 三位十六进制        |

#### 	3.4.1 转义符在shell中的应用

```
suyelu@HaiZei-Tech:~$ echo -e "\044"
$
suyelu@HaiZei-Tech:~$ echo  "\044"
\044
suyelu@HaiZei-Tech:~$ echo  $'\044'
$
suyelu@HaiZei-Tech:~$ echo  $'\44'
$
```



## 5.4、附录1：shell元字符

| 字符 | 说明                                                         |
| ---- | ------------------------------------------------------------ |
| =    | 变量名=值，为变量赋值。注意=左右紧跟变量名和值，**中间不要有空格** |
| ``   | 取命令的执行结果，与下文的$有相似之处                        |
| $    | 变量值替换，$变量名替换为shell变量的值;为避免在文本连接时混淆，请使用**${变量名}**；$0...$9 代表shell文件的参数。**$()**同``;**${}**限定变量名的范围；**$[]**整数计算，如$[1+2]，$取值的时候，括号里面只需要跟变量即可（变量可自行进行计算），不需要对括号内进行运算的变量在进行取值操作，如RX=$[RXnext-RXpre]，括号中的两个都是变量 |
| >    | prog > file 将标准输出重定向到文件。                         |
| >>   | prog >> file 将标准输出追加到文件。                          |
| <    | prog < file 从文件file中获取标准输入                         |
| <<   | 指定结束符                                                   |
| \|   | 管道命令，例：p1 \| p2， 将p1的标准输出作为p2的标准输入      |
| &    | 后台运行命令，最大好处是无需等待命令执行结束，就可以在同一命令行下继续输入命令 |
| ()   | 在子shell中执行命令,在子进程中执行                           |
| {}   | 在当前shell中执行命令，或用在变量替换的界定范围(例如上面的${变量名}用法)。 |
| []   | 字符通配，匹配括号内之一                                     |
| ;    | 命令结束符。例如p1;p2表示先执行p1,再执行p2                   |
| &&   | 前一个命令执行成功后，才继续执行下一个命令。例：p1 && p2 ;若p1执行成功后，才执行p2,反之，不执行p2; |
| \|\| | 前一个命令执行失败后，才继续执行下一个命令。例：p1 \|\| p2 ;若p1执行成功后，不执行p2,反之，才执行p2; |
| !    | 执行历史记录中的命令**!731**；匹配最近的一次命令**!echo**（以echo开头的命令)；取非**ls /dev/sda[!1]**；结果取反**! echo ok ;echo $?** |
| %    | **% 1**相当于**fg 1**                                        |
| ^    | 取非，和**!**雷同；**`^string1^string2^`**将上一命令的string1替换为string2 |
| ~    | home目录                                                     |
| #    | 注释                                                         |
| *    | 通配符，任意字符                                             |
| ?    | 通配符，任一字符                                             |
| .    | 当前目录；source (`source .zshrc` =` . ./.zshrc`)            |
| -    | 减号；上次工作目录                                           |
| :    | 真值；空命令                                                 |
| \    | 转义                                                         |
| /    | 目录分割符                                                   |

**`ctrl + r `**可以搜索以前执行过的命令。

## 5.5、附录2：ASCII码 对照表

| Bin(二进制) | Oct(八进制) | Dec(十进制) | Hex(十六进制) | 缩写/字符                   | 解释         |
| ----------- | ----------- | ----------- | ------------- | --------------------------- | ------------ |
| 0000 0000   | 0           | 0           | 00            | NUL(null)                   | 空字符       |
| 0000 0001   | 1           | 1           | 01            | SOH(start of headline)      | 标题开始     |
| 0000 0010   | 2           | 2           | 02            | STX (start of text)         | 正文开始     |
| 0000 0011   | 3           | 3           | 03            | ETX (end of text)           | 正文结束     |
| 0000 0100   | 4           | 4           | 04            | EOT (end of transmission)   | 传输结束     |
| 0000 0101   | 5           | 5           | 05            | ENQ (enquiry)               | 请求         |
| 0000 0110   | 6           | 6           | 06            | ACK (acknowledge)           | 收到通知     |
| 0000 0111   | 7           | 7           | 07            | BEL (bell)                  | 响铃         |
| 0000 1000   | 10          | 8           | 08            | BS (backspace)              | 退格         |
| 0000 1001   | 11          | 9           | 09            | HT (horizontal tab)         | 水平制表符   |
| 0000 1010   | 12          | 10          | 0A            | LF (NL line feed, new line) | 换行键       |
| 0000 1011   | 13          | 11          | 0B            | VT (vertical tab)           | 垂直制表符   |
| 0000 1100   | 14          | 12          | 0C            | FF (NP form feed, new page) | 换页键       |
| 0000 1101   | 15          | 13          | 0D            | CR (carriage return)        | 回车键       |
| 0000 1110   | 16          | 14          | 0E            | SO (shift out)              | 不用切换     |
| 0000 1111   | 17          | 15          | 0F            | SI (shift in)               | 启用切换     |
| 0001 0000   | 20          | 16          | 10            | DLE (data link escape)      | 数据链路转义 |
| 0001 0001   | 21          | 17          | 11            | DC1 (device control 1)      | 设备控制1    |
| 0001 0010   | 22          | 18          | 12            | DC2 (device control 2)      | 设备控制2    |
| 0001 0011   | 23          | 19          | 13            | DC3 (device control 3)      | 设备控制3    |
| 0001 0100   | 24          | 20          | 14            | DC4 (device control 4)      | 设备控制4    |
| 0001 0101   | 25          | 21          | 15            | NAK (negative acknowledge)  | 拒绝接收     |
| 0001 0110   | 26          | 22          | 16            | SYN (synchronous idle)      | 同步空闲     |
| 0001 0111   | 27          | 23          | 17            | ETB (end of trans. block)   | 结束传输块   |
| 0001 1000   | 30          | 24          | 18            | CAN (cancel)                | 取消         |
| 0001 1001   | 31          | 25          | 19            | EM (end of medium)          | 媒介结束     |
| 0001 1010   | 32          | 26          | 1A            | SUB (substitute)            | 代替         |
| 0001 1011   | 33          | 27          | 1B            | ESC (escape)                | 换码(溢出)   |
| 0001 1100   | 34          | 28          | 1C            | FS (file separator)         | 文件分隔符   |
| 0001 1101   | 35          | 29          | 1D            | GS (group separator)        | 分组符       |
| 0001 1110   | 36          | 30          | 1E            | RS (record separator)       | 记录分隔符   |
| 0001 1111   | 37          | 31          | 1F            | US (unit separator)         | 单元分隔符   |
| 0010 0000   | 40          | 32          | 20            | (space)                     | 空格         |
| 0010 0001   | 41          | 33          | 21            | !                           | 叹号         |
| 0010 0010   | 42          | 34          | 22            | "                           | 双引号       |
| 0010 0011   | 43          | 35          | 23            | #                           | 井号         |
| 0010 0100   | 44          | 36          | 24            | $                           | 美元符       |
| 0010 0101   | 45          | 37          | 25            | %                           | 百分号       |
| 0010 0110   | 46          | 38          | 26            | &                           | 和号         |
| 0010 0111   | 47          | 39          | 27            | '                           | 闭单引号     |
| 0010 1000   | 50          | 40          | 28            | (                           | 开括号       |
| 0010 1001   | 51          | 41          | 29            | )                           | 闭括号       |
| 0010 1010   | 52          | 42          | 2A            | *                           | 星号         |
| 0010 1011   | 53          | 43          | 2B            | +                           | 加号         |
| 0010 1100   | 54          | 44          | 2C            | ,                           | 逗号         |
| 0010 1101   | 55          | 45          | 2D            | -                           | 减号/破折号  |
| 0010 1110   | 56          | 46          | 2E            | .                           | 句号         |
| 00101111    | 57          | 47          | 2F            | /                           | 斜杠         |
| 00110000    | 60          | 48          | 30            | 0                           | 数字0        |
| 00110001    | 61          | 49          | 31            | 1                           | 数字1        |
| 00110010    | 62          | 50          | 32            | 2                           | 数字2        |
| 00110011    | 63          | 51          | 33            | 3                           | 数字3        |
| 00110100    | 64          | 52          | 34            | 4                           | 数字4        |
| 00110101    | 65          | 53          | 35            | 5                           | 数字5        |
| 00110110    | 66          | 54          | 36            | 6                           | 数字6        |
| 00110111    | 67          | 55          | 37            | 7                           | 数字7        |
| 00111000    | 70          | 56          | 38            | 8                           | 数字8        |
| 00111001    | 71          | 57          | 39            | 9                           | 数字9        |
| 00111010    | 72          | 58          | 3A            | :                           | 冒号         |
| 00111011    | 73          | 59          | 3B            | ;                           | 分号         |
| 00111100    | 74          | 60          | 3C            | <                           | 小于         |
| 00111101    | 75          | 61          | 3D            | =                           | 等号         |
| 00111110    | 76          | 62          | 3E            | >                           | 大于         |
| 00111111    | 77          | 63          | 3F            | ?                           | 问号         |
| 01000000    | 100         | 64          | 40            | @                           | 电子邮件符号 |
| 01000001    | 101         | 65          | 41            | A                           | 大写字母A    |
| 01000010    | 102         | 66          | 42            | B                           | 大写字母B    |
| 01000011    | 103         | 67          | 43            | C                           | 大写字母C    |
| 01000100    | 104         | 68          | 44            | D                           | 大写字母D    |
| 01000101    | 105         | 69          | 45            | E                           | 大写字母E    |
| 01000110    | 106         | 70          | 46            | F                           | 大写字母F    |
| 01000111    | 107         | 71          | 47            | G                           | 大写字母G    |
| 01001000    | 110         | 72          | 48            | H                           | 大写字母H    |
| 01001001    | 111         | 73          | 49            | I                           | 大写字母I    |
| 01001010    | 112         | 74          | 4A            | J                           | 大写字母J    |
| 01001011    | 113         | 75          | 4B            | K                           | 大写字母K    |
| 01001100    | 114         | 76          | 4C            | L                           | 大写字母L    |
| 01001101    | 115         | 77          | 4D            | M                           | 大写字母M    |
| 01001110    | 116         | 78          | 4E            | N                           | 大写字母N    |
| 01001111    | 117         | 79          | 4F            | O                           | 大写字母O    |
| 01010000    | 120         | 80          | 50            | P                           | 大写字母P    |
| 01010001    | 121         | 81          | 51            | Q                           | 大写字母Q    |
| 01010010    | 122         | 82          | 52            | R                           | 大写字母R    |
| 01010011    | 123         | 83          | 53            | S                           | 大写字母S    |
| 01010100    | 124         | 84          | 54            | T                           | 大写字母T    |
| 01010101    | 125         | 85          | 55            | U                           | 大写字母U    |
| 01010110    | 126         | 86          | 56            | V                           | 大写字母V    |
| 01010111    | 127         | 87          | 57            | W                           | 大写字母W    |
| 01011000    | 130         | 88          | 58            | X                           | 大写字母X    |
| 01011001    | 131         | 89          | 59            | Y                           | 大写字母Y    |
| 01011010    | 132         | 90          | 5A            | Z                           | 大写字母Z    |
| 01011011    | 133         | 91          | 5B            | [                           | 开方括号     |
| 01011100    | 134         | 92          | 5C            | \                           | 反斜杠       |
| 01011101    | 135         | 93          | 5D            | ]                           | 闭方括号     |
| 01011110    | 136         | 94          | 5E            | ^                           | 脱字符       |
| 01011111    | 137         | 95          | 5F            | _                           | 下划线       |
| 01100000    | 140         | 96          | 60            | `                           | 开单引号     |
| 01100001    | 141         | 97          | 61            | a                           | 小写字母a    |
| 01100010    | 142         | 98          | 62            | b                           | 小写字母b    |
| 01100011    | 143         | 99          | 63            | c                           | 小写字母c    |
| 01100100    | 144         | 100         | 64            | d                           | 小写字母d    |
| 01100101    | 145         | 101         | 65            | e                           | 小写字母e    |
| 01100110    | 146         | 102         | 66            | f                           | 小写字母f    |
| 01100111    | 147         | 103         | 67            | g                           | 小写字母g    |
| 01101000    | 150         | 104         | 68            | h                           | 小写字母h    |
| 01101001    | 151         | 105         | 69            | i                           | 小写字母i    |
| 01101010    | 152         | 106         | 6A            | j                           | 小写字母j    |
| 01101011    | 153         | 107         | 6B            | k                           | 小写字母k    |
| 01101100    | 154         | 108         | 6C            | l                           | 小写字母l    |
| 01101101    | 155         | 109         | 6D            | m                           | 小写字母m    |
| 01101110    | 156         | 110         | 6E            | n                           | 小写字母n    |
| 01101111    | 157         | 111         | 6F            | o                           | 小写字母o    |
| 01110000    | 160         | 112         | 70            | p                           | 小写字母p    |
| 01110001    | 161         | 113         | 71            | q                           | 小写字母q    |
| 01110010    | 162         | 114         | 72            | r                           | 小写字母r    |
| 01110011    | 163         | 115         | 73            | s                           | 小写字母s    |
| 01110100    | 164         | 116         | 74            | t                           | 小写字母t    |
| 01110101    | 165         | 117         | 75            | u                           | 小写字母u    |
| 01110110    | 166         | 118         | 76            | v                           | 小写字母v    |
| 01110111    | 167         | 119         | 77            | w                           | 小写字母w    |
| 01111000    | 170         | 120         | 78            | x                           | 小写字母x    |
| 01111001    | 171         | 121         | 79            | y                           | 小写字母y    |
| 01111010    | 172         | 122         | 7A            | z                           | 小写字母z    |
| 01111011    | 173         | 123         | 7B            | {                           | 开花括号     |
| 01111100    | 174         | 124         | 7C            | \|                          | 垂线         |
| 01111101    | 175         | 125         | 7D            | }                           | 闭花括号     |
| 01111110    | 176         | 126         | 7E            | ~                           | 波浪号       |
| 01111111    | 177         | 127         | 7F            | DEL (delete)                | 删除         |

# 六、基本系统

## 6.1 启动流程
![image-20200928161334721](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928161334721.png)

1、按开机键

2、加载BIOS（什么是BIOS，CMOS是什么）硬件信息，自检，并根据配置信息取得第一个可启动的设备，检测硬件如CPU、内存条等。

3、读取并执行第一个启动设备内MBR(什么是MBR)的boot loader。grub等)

4、根据boot loader的设置加载kernel，kernel开始检测硬件，并加载驱动（kernel接收BIOS的工作）

5、boot loader加载虚拟文件系统，并加载启动过程中需要的内核模块（USB,RAID,LVM,SCSI)

6、启动第一个进程init

7、init启动终端getty

8、运行 x windows系统

### 6.1.1 运行级别

运行级别即**run level**，linux通过不同的**run level**来使用不同的服务启动系统，**run level**可以分为以下七种：

| **run level** | 含义                    | 描述                                                    |
| ------------- | ----------------------- | ------------------------------------------------------- |
| 0             | halt                    | 系统关机                                                |
| 1             | single user mode        | 单用户模式（安全模式），在系统出问题时维护用            |
| 2             | multi-user，without nfs | 多用户，纯文本模式，不包含NFS服务                       |
| 3             | full multi-user mode    | 完整的多用户纯文本模式 （阿里云云主机就运行在该模式上） |
| 4             | unused                  | 系统保留                                                |
| 5             | X11                     | 在run level 3的基础上加载X Windows                      |
| 6             | reboot                  | 重启                                                    |

对于run level机制的实现，现在有三种方式：

**1、传统的System V init**

这种广为流传的方式至今仍被各种Linux distros所采用，在该方式下，init进程启动后第一时间就会读取文件**`/etc/inittab`**，该文件负责初始化系统，设置系统run level及执行各run level对应要执行的命令。

**2、UpStart**

**3、最新的systemd方式**

Systemd提供了比 UpStart 更激进的并行启动能力，采用了 socket / D-Bus activation 等技术启动服务。一个显而易见的结果就是：更快的启动速度。

为了减少系统启动时间，systemd的目标是：

- 尽可能启动更少的进程

- 尽可能将更多进程并行启动

同样地，UpStart 也试图实现这两个目标。UpStart 采用事件驱动机制，服务可以暂不启动，当需要的时候才通过事件触发其启动，这符合第一个设计目标；此外，不相干的服务可以并行启动，这也实现了第二个目标。

下图演示了UpStart相比sysVinit的改进：

![image-20200928162835281](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928162835281.png)

systemd能够更进一步提高并发性，即便对于那些UpStart认为存在相互依赖而必须串行的服务，比如Avahi和D-Bus也可以并发启动。从而实现如下图所示的并发启动过程：

![image-20200928163004799](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928163004799.png)

## 6.2、配置文件

### 6.2.1 全局配置文件

#### 6.2.1.1 系统初始化

| /etc/init       | **运行级别、控制台数量** |
| --------------- | ------------------------ |
| /etc/timezone   | 时区                     |
| /etc/inetd.conf | 超级进程                 |

#### 6.2.1.2 文件系统

| /etc/fstab | 开机时挂载的文件系统 |
| ---------- | -------------------- |
| /etc/mtab  | 当前挂载的文件系统   |

#### 6.2.1.3 用户系统

| /etc/passwd  | 用户信息             |
| ------------ | -------------------- |
| /etc/shadow  | 用户密码（加密过的） |
| /etc/group   | 群组信息             |
| /etc/gshadow | 群组密码             |
| /etc/sudoers | sudoer 列表          |

#### 6.2.1.4 Shell

| /etc/shell     | 可用的shell列表       |
| -------------- | --------------------- |
| /etc/inputrc   | ReadLine控件设定      |
| /etc/profile   | 用户首选项            |
| /etc/bashrc    | bash配置文件          |
| /etc/zsh/zshrc | zsh配置文件（全局的） |

**`/etc/zsh/zshrc`**是全局的，打开任何一个zsh都会执行。

**`.zshrc`**：是个人的zsh资源配置文件

```sh
man zsh
```

![image-20200928165638200](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928165638200.png)

vim、bash、zsh都分了全局和个人的配置文件。

#### 6.2.1.5 系统环境

| /etc/environment   | 环境变量               |
| ------------------ | ---------------------- |
| /etc/updatedb.conf | 文件检索数据库配置信息 |
| /etc/issue         | 发行信息               |
| /etc/issue.net     |                        |
| /etc/screenrc      | 屏幕设定               |

#### 6.2.1.6 网络

| /etc/iftab              | 网卡MAC地址绑定    |
| ----------------------- | ------------------ |
| /etc/hosts              | 主机列表           |
| /etc/hostname           | 主机名             |
| /etc/resolv.conf        | 域名解析服务器地址 |
| /etc/network/interfaces | 网卡配置信息       |

### 6.2.2 用户配置文件

`.zshrc`、`.zprofle`、`.zlogout`

## 6.3 环境变量

环境变量是作用在整个系统中的变量，很多软件工作的时候都需要读取环境变量的值来确定其工作方式，比如cd。

环境变量命名通常使用大写字母。`$`符后面加上环境变量的名称，系统将不会直接调用这个变量的字符串。

相关命令：env export

### 6.3.1 常见环境变量

PATH、HOME、SHELL、LANG、HISTSIZE

![image-20200928170722022](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928170722022.png)

## 6.4 软件管理

不同分支的Linux版本中，软件有默认的安装方式，如下是软件安装工具与不同分支系统的配对：

- ubuntu <=> apt
- yum <=> redhat
- zypper <=> suse

```sh
获取可更新的软件列表，更新缓存：apt update

设置下载源的文件：/etc/apt/sources.list

更新系统软件：apt upgrade

安装软件：apt install 软件名

搜索软件包：apt-cache search 软件名

卸载软件：apt remove 软件名

查看安装的所有软件：apt list
```

## 6.5 文件系统与挂载

### 6.5.1 目录结构

![image-20200928172910234](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928172910234.png)

**`/etc`**：保存系统配置

**`/home`**：该目录保存的是所有用户的家目录，/home相当于一个社区，个人的家目录是$HOME，比如lj用户的家目录是/home/lj，而非/home

**`/mnt`**：mount，挂载分区

**`opt`**：可选的

**`/tmp`**：临时文件夹，如果进程结束，该文件夹的文件会丢失

**`/var`**:可变文件夹，比如log、网站更新的内容等。

### 6.5.2 挂载点

利用sshfs命令挂载。

安装sshfs：

```sh
sudo apt install sshfs
```

```sh
sshfs username@host:dir mountpoint
sshfs -o nonempty username@host:dir mountpoint #当挂载点不是空文件夹时使用
```

例如：

```sh
sshfs lj@47.115.90.255:./test mnt/
```

将47.115.90.255服务器上根目录下的test文件夹挂载到当前主机的当前目录的mnt/。如果关闭主机，挂载就无效了。

如果挂载u盘就直接用mount。

解挂载：

```sh
umount mnt
```

# 七、Linux系统信息

## 7.1 系统信息

| 命令   | 功能                             |
| ------ | -------------------------------- |
| uptime | 打印系统运行时长和平均负载       |
| w      | 当前登录用户列表及正在执行的任务 |
| who    | 显示当前登录系统的用户信息       |
| whoami | 打印当前有效的用户名称           |
| last   | 显示用户最近登录信息             |
| uname  | 打印当前系统信息                 |
| date   | 显示或设置系统时间与日期         |
| cal    | 显示日历                         |

## 7.2 uptime 系统运行时长，平均负载

语法：**`uptime [phsV]`**

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928220627526.png" alt="image-20200928220627526"  />

## 7.3 w 获取当前登录用户和正在执行的进程

语法：**`w [husfV] <user> <...>`**

options：

​		**`h`**：不打印头信息

​		**`s`**：使用短输出格式

​		**`f`**：切换显示FROM项，默认显示

![image-20200928220937838](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928220937838.png)

| USER       | TTY                    | FROM       | LOGIN@   | IDLE     | JCPU | PCPU               | WHAT                   |
| ---------- | ---------------------- | ---------- | -------- | -------- | ---- | ------------------ | ---------------------- |
| 登录用户名 | 登录后系统分配的终端号 | 远程主机名 | 登录时间 | 空闲时间 | ①    | 当前进程所占用时间 | 当前进程正在执行的命令 |

①和该终端相连的所有进程占用的时间，包含当前正在执行的后台作业

FROM是云主机看到的本地IP经过层层NAT之后的公网IP，并非本地IP。

### wall：给所有用户发送消息

![image-20200928221826666](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928221826666.png)

**`wall`**命令实际就是**<u>打开了/dev/pts下的所有文件，即设备文件，然后给所有文件都写入这个信息</u>**。

![image-20200928222538625](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928222538625.png)

**==目前的问题是，普通用户使用wall，必须加sudo，root用户才会收到该消息。==**

原因解释：参考第六章”文件特殊权限“中，

![image-20200929220700367](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929220700367.png)

可以看到，root用户所在TTY是pts/1，虽然lj用户在执行wall命令的时候通过set_gid可以获得tty的权限，但是因为tty对/dev/pts/1没有任何权限，也就是说lj用户对/dev/pts/1是没有任何权限的，所以没法通知到root用户。



![image-20200928223334513](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928223334513.png)

有的文件如：etc/shadow)普通用户没有权限访问，但是也可以使用passwd命令修改密码往shadow文件中写内容了。上图中第一个命令结果中的`s`是setgid，第二个命令结果中的`s`是setuid。

## 7.4 who 显示当前登录系统的用户信息

语法：**`who [option] <file | arg1 arg2>`**

选项：

​	**`-H`**：显示各栏的标题信息列

​	**`-u`**：显示空置时间

​	**`-q`**：只显示登入系统的用户名称和总人数

![image-20200928230507307](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928230507307.png)

## 7.5 whoami 打印当前有效的用户名称

语法：**`whoami`**

![image-20200928230706228](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928230706228.png)

## 7.6 last 显示用户最近登录信息

语法：**`last [fnx] <username...> <tty...>`**

选项：

​		**`-f`**: "file"，指定记录文件

​		**`-n `**: "num"，指定输出记录数

​		**`-x`**：显示系统关机，重新关机等信息

![image-20200928231100104](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928231100104.png)

![image-20200928231223723](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928231223723.png)

![image-20200928231210895](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928231210895.png)

回顾：

1、last命令使用的数据文件在什么位置？

2、什么是数据文件？

3、数据文件相对于普通文件有什么特点？



## 7.7 uname 打印当前系统信息

语法：**`uname [options]`**

参数：

​	**`-a`**: 全部信息

​	**`-m`**:电脑类型

​	**`-n`**: 网络上主机的名称

​	**`-v`**: os版本

​	**`-p`**: 处理器类型

​	**`-i`**: 硬件平台

​	**`-o`**: 操作系统名称

![image-20200928231507823](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928231507823.png)

## 7.8 date 显示或设置系统时间与日期

语法： **`date [dsu] <参数>`**

选项：

​	**`-d  ”string“`**: 显示字符串所指的日期 

​	**`-s  ”string“`**: 设置时间

​	**`-u`**：显示GMT(如果是CST的情况下)

参数： **`<+日期格式>`**：显示使用的日期格式

![image-20200928232022267](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928232022267.png)

```sh
#51分钟后的时间
date -d "51 minutes"
```

现在时间都是基于NTP自动同步的。多机系统都是基于NTP同步，保证各个主机的时间一致。

```sh
man ntp_gettime
```

![image-20200928234228739](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928234228739.png)

## 7.9 cal 显示日历

语法：**`cal [选项] <参数>`**

选项：

​	**`-1, -3`**: 显示最近一个月和三个月的日历

​	**`-j`**: 显示一年的第几天

​	**`-y`**: 显示当前年

参数：

​	月：指定月份

​	年：指定年份

![image-20200928234358245](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928234358245.png)

![image-20200928234412456](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928234412456.png)

## 7.10 dstat

可以清楚看到CPU、磁盘、网络的使用情况。

![image-20200928234629795](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928234629795.png)

## 7.11 nmon

安装：**`sudo apt install nmon`**

执行**`nmon`**命令：

![image-20200928234853609](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928234853609.png)

依照上图中查看相应部分的字符，如在该界面输入m就会看到内存的使用情况；c查看cpu的使用情况等等。

![image-20200928235633294](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200928235633294.png)

# 八、文件与目录

## 8.1 目录

| 命令  | 功能             |
| ----- | ---------------- |
| cd    | 切换当前工作目录 |
| pwd   | 打印当前工作目录 |
| mkdir | 创建目录         |
| rmdir | 删除目录         |

- 绝对路径 : 以/home/lj为起点
- 相对路径：.表示当前目录

### 8.1.1 cd 切换工作目录

```sh
cd /etc #直接切换到/etc目录
cd .. #切换到上层目录
cd .  #切换到当前目录
cd 	  #回到自己的家目录
cd ~  #回到自己的家目录
cd -  #回到上次工作目录
```

`cd ~name`： 回到name用户的家目录

### 8.1.2 pwd 打印当前工作目录

语法：**`pwd [-LP]`**

​	**`L`**：显示逻辑工作目录

​	**`P`**:显示物理工作目录

![image-20200929000649687](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929000649687.png)

连接文件，`ls -ald`显示目录信息

### 8.1.3 mkdir 创建目录

语法：**`mkdir [pm] <dir>`**

​	**`-p`**:自动创建父目录

​	**`-m`**: 设置权限

![image-20200929134515163](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929134515163.png)

要创建test22目录，但是它的父目录test1和test11不存在，所以不能创建。

![image-20200929134751961](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929134751961.png)

加上`-p`之后，就会自动创建父目录，如果test11不存在就创建test11目录；如果test1不存在，就创建test1目录。

创建的目录默认的权限是775，如果想在创建目录的同时也设置权限，可以加上`-m`选项，如下是创建了一个555权限的目录。

![image-20200929135010057](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929135010057.png)

umask：设置掩码，默认值是002

![image-20200929135339115](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929135339115.png)

创建的目录或文件的权限是默认权限减去umask，例如目录的默认权限是777，但是减去umask，所以创建的目录的权限是777- 002 = 775；文件的默认权限是666，减去umask就是666 - 002 = 664。

![image-20200929135628635](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929135628635.png)

可以通过`umask xxx`设置umask的值。

`env`命令查看环境变量。

### 8.1.4 rmdir 删除目录

语法：**`rmdir [p] <dir>`**

​	**`p`**：删除祖先

只能删除空的目录。

### 8.1.5 思考

1、我们自己写的程序在编译后，使用命令`./a.out `执行，这里的`./`是什么意思？

答：`./`是相对路径，`a.out`是可执行文件。

2、**`PATH="$PATH":/home/lj/bin`**的含义是什么？

答：`=`表示是赋值语句，`"$PATH"`是获得PATH变量的值，`:/home/lj/bin`是字符串拼接，将/home/lj/bin这个路径加入到PATH变量中。

## 8.2 文件与目录的管理

| 命令     | 功能               |
| -------- | ------------------ |
| ls       | 显示文件及目录信息 |
| cp       | 拷贝               |
| rm       | 删除               |
| mv       | 移动               |
| basename | 取文件名           |
| dirname  | 取目录名           |

`ls` :缺省参数，就显示当前目录的文件内容

`ls dir`： 显示指定dir的目录的内容

`ls dir1 dir2`: 显示多个目录的内容，显示顺序有一定的规则

![image-20200929140617095](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929140617095.png)

如上，`ls . / /etc`是先显示的`/`, 然后`.` ，最后`/etc`。

`ls -a` : 显示所有文件

`ls -A`:  显示所有文件但不包含`.`和`..` 。（该命令的设计是为了避免在写脚本的时候，进入无限死循环。）

`ls -d`： 显示目录信息，通常配合`ls -aldhi`（或者拆开：`ls -a -l -d -h -i`）使用，这种方式是以长列表的人类可读的形式查看目录相关信息（权限，大小等）, `i`表示inode。

![image-20200929141437929](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929141437929.png)

### 8.2.1 cp 拷贝

语法：**`cp [irapdslu] <sour> <dest>`**

选项：

​	`-i`:若文件存在，询问用户

​	`-r`：递归复制 (拷贝目录)

​	`-a`: pdr的集合

​	`-p`:连同文件属性一起拷贝

​	`-d`:若源文件为连接文件的属性，则复制连接文件的属性

​	`-s`:拷贝为软连接

​	`-l`:拷贝为硬链接

​	`-u`:源文件比目的文件新才拷贝，常用于备份系统。

![image-20200929153047996](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929153047996.png)

inode 对应很多block

尝试：`cp file1 file2 ... dir`

![image-20200929153814248](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929153814248.png)

### 8.2.2 rm 删除

语法：`rm [irf] <dir_or_file>`

选项：

​	`-i`: 互动模式，删除之前会有提示信息

​	`-r`: 递归删除

​	`-f`: force

`rm -rf *`的实际操作是取消了文件系统和磁盘的映射关系，数据其实还在磁盘中，以二进制形式存储着，这个时候如果再进行了其他操作，该部分的磁盘数据就可能被覆盖，所以执行了这个之后如果后悔了，应该立即关机，将电脑作为磁盘插到另一个机器上。

### 8.2.3 mv 移动

- 语法：`mv [ifu] <source...>  <dest>`
    - `mv source1 source2 source3 dir`
    - 也是相当于重命名

选项：

​	`-i`: 互动模式

​	`-f`: force

​	`-u`：源文件更新才会移动

如果想保留旧文件，就用cp，否则用mv。

### 8.2.4 dirname和basename的用法

![image-20200929154727609](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929154727609.png)

​	多用于脚本编写。

## 8.3 文件内容的查阅

| 命令 | 功能                         |
| ---- | ---------------------------- |
| cat  | 正向连续读                   |
| tac  | 反向连续读                   |
| nl   | 输出行号显示文件             |
| more | 一页一页地显示文件内容       |
| less | 与more相似，但是可以上下翻看 |
| head | 只看头几行                   |
| tail | 只看末尾几行                 |
| od   | 以二进制方式查看文件内容     |

### 8.3.1 cat 正向连续读

语法：`cat [-AbEnTv] <file>`

选项：

​	`-A`:相当于-vET，可以用于字符检测

​	`-v`:列出看不到的字符

​	`-E`:显示断行符为$

​	`-T`:显示TAB为^I

​	`-b`:列出行号

​	`-n`:列出行号，连同空行也编号

![image-20200929155414004](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929155414004.png)

![image-20200929155454139](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929155454139.png)

### 8.3.2 tac 反向连续读

刚好与cat相反，从最后一行开始打印。按行反着读。

![image-20200929155632529](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929155632529.png)

### 8.3.3 nl 输出行号显示文件

语法：`nl [-bnw] <file>`

选项：

​	`-b`:行号指定方式

​			`-b a`:相当于cat -n

​			`-b t`:相当于cat -b

​	`-n`:列出行号的表示方法

​			`-n ln`:行号在屏幕最左边显示

​			`-n rn`:行号在自己字段的最右边显示

​			`-n rz`: 行号在自己字段的最右边显示，前面自动补全0

​	`-w <num>`: 行号所占位数 

![image-20200929160020589](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929160020589.png)

![image-20200929160051926](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929160051926.png)

![image-20200929160121598](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929160121598.png)

### 8.3.4 more 按页查看

语法：`more file`

​		`/string`:向下查找string关键字

​		`:f`:显示文件名称和当前显示的行数

​		`q`:离开

​	   按空格是下一行

### 8.3.5 less 按页查看

语法：`less file`

​		`/string`:向下查找    `n`：继续向下查找

​		`/?string`:反向查找   `N`:  继续反向查询

比more更好用，可以上下两个方向查询。

### 8.3.6 head 查看头几行

语法：`head [-n num] <file>`

​		`-n num`:显示前num行

​		`-n -num`:除了后num行外，其他的都显示

![image-20200929160921722](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929160921722.png)



### 8.3.7 tail 查看末尾几行

语法：`tail [-n num] <file>`

​		`-n num`:显示文件的后num行

​		`-n +num`:除了前num行，其他的都显示

![image-20200929161154707](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929161154707.png)

### 8.3.8 练习：如何查看一个文件的第101行到120行

查看方式：`head -n 120 file | tail -n 20`

### 8.3.9 od 二进制文件查看

语法：`od [-t TYPE] <file>`

​		`-t` :

​			`a`:默认字符输出

​			`c`:ASCII字符输出

​			`d[size]` :十进制输出，每个数占用size bytes

​			`f[size]`:浮点数输出...

​			`o[size]`：八进制输出...

​			`x[size]`:十六进制输出...



## 8.4 修改文件时间与新建文件

- 文件的三个时间

    - mtime：内容数据改动时才更新这个时间 （modify time）
- ctime：文件的权限，属性改动时更新这个时间 （chmod time）
    - atime：文件的内容被取用access（即访问文件）时，更新这个时间 （access time）--大多数是没有的

    使用方式：`ls -l --time=ctime /etc/hostname`

![image-20200929162310298](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929162310298.png)

- `touch [-acdmt] <file>`  多用来创建空白文件
  
    - `-a`:仅修改访问时间
    
    - `-c`:仅修改文件的时间，若文件不存在，不新建
    
    - `-d`: 修改文件日期
    
    - `-m`:仅修改mtime
    
    - `-t`:修改文件时间[yymmddhhmm]
    
        

## 8.5 文件的隐藏属性 chattr

- `chattr [+-=][ASacdistu] <file_or_dir>`
  
    - `A`:不修改atime
    - `S`:同步写入，真实写到磁盘
    - `a`:只能增加数据，通常是用于日志
    - `c`:自动压缩，解压，通常用于备份系统
    - `d`:不会被dump程序备份
    - `i`:不能删除，修改，建立连接
    - `s`:文件删除时，直接从磁盘删除。正常情况下删除只是将映射关系删除了，但是数据还在磁盘中，加了该选项后， 磁盘中的数据会被全0覆盖。
    - `u`:文件删除时，数据内容存在磁盘中
- `lsattr [-adR] <file_or_dir>`
    - `-a`：打印隐藏文件的隐藏属性
    - `-d`:  如果是目录，仅打印目录的信息
    - `-R`:  递归
    
    ![image-20200929162933869](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929162933869.png)

![image-20200929163027998](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929163027998.png)

![image-20200929163111936](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929163111936.png)

如果想删除带有该属性的文件，就减去`i`选项:

![image-20200929163227076](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929163227076.png)

## 8.6 文件的特殊权限set_uid、set_gid、sticky bit

- `set_uid`
- `set_gid`
- `sticky bit`

| 权限       |      | 作用的对象                                   | 效果                                   |
| ---------- | ---- | -------------------------------------------- | -------------------------------------- |
| set_uid    | s    | 二进制程序文件（编译好的可执行文件），非脚本 | 用户在执行该程序时获取程序所有者权限   |
| set_gid    | s    | 目录和二进制程序文件                         | 用户在该目录里，有效组变为目录所属组   |
| sticky bit | t    | 目录 （数据保护）                            | 在该目录下，用户只能删除自己创建的内容 |

set_uid和set_gid可以使得用户在执行某些命令的时候获得user或group权限；sticky bit用于数据安全保护，可写可读但是不能删。

例如：

1、普通用户对`/etc/shadow`文件没有读写权限，但是又可以通过`passwd`命令去写这个文件。

![image-20200929171857239](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929171857239.png)

`s`表示`set_uid`，即`user`这个用户位置。如果原先`s`的位置有x权限，那么就是小写s，否则就是大写S。对于这个命令来说，lj是others用户，当lj执行这个命令的时候，会获得该命令的所有者（此处即root，拥有rws权限）的权限。

2、`set_gid`的 `s` 放在`group`这个用户的`x`权限位置处，如果此前有`x`权限，则为小写`s`，否则为大写`S`。

![image-20200929215038655](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929215038655.png)

wall命令的tty组有set_gid权限，而tty对设备文件如`/dev/pts/0`有`w`权限，所以当用户执行`wall`命令的时候，有效组就变成了`tty`，自然也就有了对设备文件`/dev/pts/0`等的写的权限。

3、`sticky bit`权限的目录，该目录下只能删除自己创建的内容。

![image-20200929215558591](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200929215558591.png)



### 练习（重点）

1. 新建一个群组TestGroup

    `groupadd TestGroup`

2. 在自己的Linux系统中新建两个用户userA和userB

    `useradd -G TestGroup userA`

    `useradd -G TestGroup userB`

3. 假设现在有一个项目需要由A，B两位用户同时对项目有读写权限，使用root用户创建一个项目目录，实现A，B两位用户都能够读写新建文件。

    （1）UserA新建的文件，可以直接被UserB读写！

    （2）UserA  UserB只能删除自己创建的内容

    （3）其他用户不能读取该项目目录
    
    自我思考：该文件应该有的权限如下
    
    ​	`-rwxr-s--t userA TestGroup ... dir_name`

## 8.7 命令与文件的查询

| 命令    | 功能                 |
| ------- | -------------------- |
| which   | 寻找可执行文件       |
| whereis | 寻找特定文件         |
| locate  | 搜索文件(可部分查找) |
| find    | 多样化高级查找       |



### 8.7.1 which 寻找可执行文件

查找PATH路径下所有的可执行文件（找到要找的PATH路径下的第一个可执行文件后就不会往后找了）



### 8.7.2 whereis 寻找特定文件

`whereis [-bmsu] <file_or_dir>`

​		`-b`: 只查找二进制文件

​		`-m`: 只查找manual路径下的文件

​		`-s`: 只查找source源文件



### 8.7.3 locate 模糊定位

`locate [-ir] keyword`

​		`-i`:  忽略大小写

​		`-r`:  后面可接正则表达式

如果想查找最新的系统的关键词，可以使用`sudo updatedb`更新要查找的数据库。

![image-20200930105841502](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200930105841502.png)

相关文件：`/etc/updatedb.conf`、`/var/lib/mlocate`

### 8.7.4 find 高级查找

- `find [PATH] [option] [action]`
    - 与时间相关的参数：`-atime`, `-ctime`，`-mtime`
        - `-mtime n`：n天前的”一天之内“修改的文件 amin
        - `-mtime +n`:  n天之前，不包含n，修改过的文件
        - `-mtime -n`: n天之内，包含n，修改过的文件
        - `-newer file`: 比file还要新的文件
    - 与用户或用户组相关的参数；
        - `-uid n`: 用户UID为n
        - `-gid n`:  群组Gid为n
        - `-user name`: 用户名为name
        - `-group name`: 群组名为name
        - `nouser`: 文件所有者不存在
        - `nogroup`: 文件所在组不存在
    - 与文件权限及名称有关的参数：
        - `-name filename`: 文件名为filename
        - `-size [+-] SIZE`:  查找比SIZE大或小的
        - `-type TYPE`: f b c d l s p
        - `-perm mode`:  mode刚好等于的文件
        - `-perm -mode`: 全部包含mode的文件
- `find -exec ls -l {} \;`   -->`-exec`是action开始，`\;`是action结束，`{}`表示把找到的结果放到其中，`ls -l`就是执行的action。

1、查找比./test/a.c还新的文件：

![image-20200930110602229](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200930110602229.png)

2、查找当前目录下三天之内被修改过的文件：

```sh
find . -mtime -3
```

3、上面所有可以用的选项都用上的情况示例：

```sh
find /home -mtime -3 newer ./test/a.c -user lj -name "*.c" -size +12c -type f -perm -444 -exec ls -al {} \;  2>/dev/zero
```

/dev/zero或/dev/null是数据黑洞，可以将错误重定向到该文件中。

`-perm -444`意思是要找的文件里面包含444权限。

### 8.7.5 练习

统计某个目录下如下各类型文件的总行数：

- .c
- .cpp
- .sh
- .h

求总行数: 可以用`wc -l`、`cat -n`等方式。

![image-20200930113810528](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20200930113810528.png)



# 九、数据提取操作

| 命令  | 说明                 |
| ----- | -------------------- |
| cut   | 切分                 |
| grep  | 检索                 |
| sort  | 排序                 |
| wc    | 统计字符、字数、行数 |
| uniq  | 去重                 |
| tee   | 双向重导项           |
| split | 文件切分             |
| xargs | 参数代换             |
| tr    | 替换、压缩和删除     |

## 9.1 tr 对标准输入的字符替换，压缩，删除

语法：`tr [cdst] <字符集>  <字符集>`

​		`c`: 取代所有不属于第一字符集的字符

​		`d`: 删除所有不属于第一字符集的字符

​		`s`: 将连续重复的字符以单独一个字符表示

​		`t`：先删除第一字符集较第二字符集多出的字符

![image-20201002080126876](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201002080126876.png)

```sh
#替换单个字符
lj@Aliyun test % echo "abcdefghjl" | tr "ac" "111"                  [0]
1b1defghjl
```

```sh
#删除字符集
lj@Aliyun test % echo "abcdefghjl" | tr -d "abcl"                   [0]
defghj
```

```sh
#压缩字符
lj@Aliyun test % echo "abcde         fghjl" | tr -s " "             [0]
abcde fghjl
```

```sh
#转换为大写
lj@Aliyun test % echo "abcde         fghjl" | tr -s " " | tr "[:lower:]" "[:upper:]"       [0]
ABCDE FGHJL
```

### 词频统计

```sh
#统计词频
#1、将不是a-z或A-Z的字符替换为换行，并进行压缩、排序（以字符方式排序）、去重计数、按数字方式逆序排序，显示排序前十的结果，即出现次数最多的前10个单词
lj@Aliyun test % cat data.log | tr -c -s  "a-zA-Z" "\n" | sort | uniq -c | sort -n -r | head
     20 a
      8 int
      8 d
      4 Time
      4 Sun
      4 stdio
      4 Sep
      4 scanf
      4 return
      4 qq
```



## 9.2 cut 切分

语法：`cut [-dfc] <file>`

​		`-d c`：以c字符分割

​		`-f num`： 显示num字段的内容【n- ； n-m；-m 】

​		`-b num`： 字节

​		`-c num`：字符

举例：

1、bash下export的内容：

```sh
declare -x AUTOJUMP_ERROR_PATH="/home/lj/.local/share/autojump/errors.log"
declare -x AUTOJUMP_SOURCED="1"
declare -x HOME="/home/lj"
declare -x LANG="en_US.UTF-8"
declare -x LC_TERMINAL="iTerm2"
declare -x LC_TERMINAL_VERSION="3.3.12"
declare -x LESS="-R"
declare -x LESSCLOSE="/usr/bin/lesspipe %s %s"
declare -x LESSOPEN="| /usr/bin/lesspipe %s"
declare -x LOGNAME="lj"
declare -x LSCOLORS="Gxfxcxdxbxegedabagacad"
```

```sh
#以空格进行切分，并显示第三段及之后的内容
export | cut -d " " -f 3-
#以空格进行切分，并显示第三段的内容，针对例子中的第9行就会出现错误，显示的是LESSOPEN="|
export | cut -d " " -f 3
#以空格进行切分，并显示第3到4段的内容
export | cut -d " " -f 3-4
```

```sh
#按字符切,显示从第12个字符往后的内容
export | cut -c 12-
```

2、将$PATH的最后一个路径输出

```sh
lj@Aliyun ~ % echo $PATH                                                  [127]
/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin
lj@Aliyun ~ % echo $PATH | cut -d : -f 9                                    [0]
/snap/bin
```

3、**思考**：如何显示切割的内容的最后一个，在不知道是第几块的情况下。



## 9.3 grep 检索
-

5、累加/etc/passwd中uuid大于1000的uuid

![image-20201028173722192](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028173722192.png)

## 9.5 sed 

![image-20201028173956657](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028173956657.png)

1、新建文件test.txt，写上如下内容：

```text
Maureen is lj.
Maureen is lj2.
```

![image-20201028174423622](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028174423622.png)

2、修改文件中的内容

![image-20201028174557646](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028174557646.png)

3、指定行进行替换操作：第二行的LJ替换为ABC

![image-20201028175112492](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028175112492.png)

## 9.6 sort 排序

语法：`sort [-fbMnrtuk] <file_or_stdio>`

​		`-f`: 忽略大小写

​		`-b`: 忽略最前面的空格符

​		`-M`: 以月份名称排序

​		`-n`: 以纯数字方式排序

​		`-r`: 反向排序

​		`-u`: uniq

​		`-t`: 分隔符，默认[TAB]

​		`-k`: 以哪个区间排序

```sh
#以用户名排序/etc/passwd的内容
lj@Aliyun ~ % cat /etc/passwd | sort                                               [0]
_apt:x:104:65534::/nonexistent:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
_chrony:x:108:117:Chrony daemon,,,:/var/lib/chrony:/usr/sbin/nologin
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
games:x:5:60:games:/usr/games:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
lj:x:1000:1000:,,,:/home/lj:/usr/bin/zsh
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
messagebus:x:103:107::/nonexistent:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
ntp:x:106:111::/nonexistent:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
root:x:0:0:root:/root:/bin/bash
sshd:x:107:65534::/run/sshd:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
syslog:x:102:106::/home/syslog:/usr/sbin/nologin
systemd-network:x:100:102:systemd Network Management,,,:/run/systemd/netif:/usr/sbin/nologin
systemd-resolve:x:101:103:systemd Resolver,,,:/run/systemd/resolve:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
uuidd:x:105:109::/run/uuidd:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
#以用户名反向排序
lj@Aliyun ~ % cat /etc/passwd | sort  -r                                           [0]
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
uuidd:x:105:109::/run/uuidd:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
systemd-resolve:x:101:103:systemd Resolver,,,:/run/systemd/resolve:/usr/sbin/nologin
systemd-network:x:100:102:systemd Network Management,,,:/run/systemd/netif:/usr/sbin/nologin
syslog:x:102:106::/home/syslog:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
sshd:x:107:65534::/run/sshd:/usr/sbin/nologin
root:x:0:0:root:/root:/bin/bash
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
ntp:x:106:111::/nonexistent:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
messagebus:x:103:107::/nonexistent:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
lj:x:1000:1000:,,,:/home/lj:/usr/bin/zsh
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
games:x:5:60:games:/usr/games:/usr/sbin/nologin
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
_chrony:x:108:117:Chrony daemon,,,:/var/lib/chrony:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
_apt:x:104:65534::/nonexistent:/usr/sbin/nologin
#用uid排序,即第三列，用:分隔的第三列，-n是以纯数字的方式排序
lj@Aliyun ~ % cat /etc/passwd | sort -t : -k 3 -n                                  [0]
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
systemd-network:x:100:102:systemd Network Management,,,:/run/systemd/netif:/usr/sbin/nologin
systemd-resolve:x:101:103:systemd Resolver,,,:/run/systemd/resolve:/usr/sbin/nologin
syslog:x:102:106::/home/syslog:/usr/sbin/nologin
messagebus:x:103:107::/nonexistent:/usr/sbin/nologin
_apt:x:104:65534::/nonexistent:/usr/sbin/nologin
uuidd:x:105:109::/run/uuidd:/usr/sbin/nologin
ntp:x:106:111::/nonexistent:/usr/sbin/nologin
sshd:x:107:65534::/run/sshd:/usr/sbin/nologin
_chrony:x:108:117:Chrony daemon,,,:/var/lib/chrony:/usr/sbin/nologin
lj:x:1000:1000:,,,:/home/lj:/usr/bin/zsh
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
```

```sh
#^表示行开始，$表示行末,^$表示行开始就是行末，即空行
# 输出last信息中不包含空行的
lj@Aliyun ~ % last                       [0]
lj       pts/0        113.87.180.35    Fri Oct  2 06:39   still logged in

wtmp begins Fri Oct  2 06:39:01 2020
lj@Aliyun ~ % last | grep -v ^$                                                [0]
lj       pts/0        113.87.180.35    Fri Oct  2 06:39   still logged in
wtmp begins Fri Oct  2 06:39:01 2020
# 输出不包含空行和begins信息的
lj@Aliyun ~ % last | grep -v ^$ | grep -v begins                 [0]
lj       pts/0        113.87.180.35    Fri Oct  2 06:39   still logged in
# 将上面的结果用 空格进行切分,获取名字段
lj@Aliyun ~ % last | grep -v ^$ | grep -v begins  | cut -d " " -f 1
lj
# 对上面的结果进行排序并去重
lj@Aliyun ~ % last | grep -v ^$ | grep -v begins  | cut -d " " -f 1 | sort -u
lj
```



## 9.7、wc 统计字符，字数，行数

语法：`wc [-lwm] <file_or_stdin>`

​		`-l`: 仅列出行号

​		`-w`: 仅列出多少字

​		`-m/-c`: 仅列出多少字符

```sh
#查找test目录下的.c文件代码
lj@Aliyun test % find . -name "*.c"                                 [0]
./mnt/1.c
./mnt/a.c
./c.c
./2.c
./a.c
./3.c
./b.c
# 输出上面的结果
lj@Aliyun test % find . -name "*.c" -exec cat {} \;                 [0]
/*************************************************************************
	> File Name: a.c
	> Author: Maureen
	> Mail: 1437867946@qq.com
	> Created Time: Sun 27 Sep 2020 04:22:41 PM CST
 ************************************************************************/

#include<stdio.h>

int main() {
    int a;
    scanf("%d", &a);
    printf("a = %d\n", a);
    return 0;
}
/*************************************************************************
	> File Name: a.c
	> Author: Maureen
	> Mail: 1437867946@qq.com
	> Created Time: Sun 27 Sep 2020 04:22:41 PM CST
 ************************************************************************/

#include<stdio.h>

int main() {
    int a;
    scanf("%d", &a);
    printf("a = %d\n", a);
    return 0;
}
cat: ./2.c: No such file or directory
/*************************************************************************
	> File Name: a.c
	> Author: Maureen
	> Mail: 1437867946@qq.com
	> Created Time: Sun 27 Sep 2020 04:22:41 PM CST
 ************************************************************************/

#include<stdio.h>

int main() {
    int a;
    scanf("%d", &a);
    printf("a = %d\n", a);
    return 0;
}
/*************************************************************************
	> File Name: a.c
	> Author: Maureen
	> Mail: 1437867946@qq.com
	> Created Time: Sun 27 Sep 2020 04:22:41 PM CST
 ************************************************************************/

#include<stdio.h>

int main() {
    int a;
    scanf("%d", &a);
    printf("a = %d\n", a);
    return 0;
}

#统计上面结果中总的行数
lj@Aliyun test % find . -name "*.c" -exec cat {} \; | wc -l         [0]
60
#统计上面结果中总的字符数
lj@Aliyun test % find . -name "*.c" -exec cat {} \; | wc -c         [0]
1492
#统计上面结果中总的单词数
lj@Aliyun test % find . -name "*.c" -exec cat {} \; | wc -w         [0]
148
```



## 9.8 uniq 去重

语法：`uniq [-ic]`

​	`-i`: 忽略大小写字符的不同

​	`-c`: 进行计数

```sh
#统计不同用户登录次数
lj@Aliyun test % last | grep -v ^$ | grep -v begins  | cut -d " " -f 1 | sort | uniq -c
      1 lj
```



## 9.9 tee 双向重导项

语法:`tee [-a] file`

​		`-a` : append

双向重导项：既要写到文件中，又要看到屏幕输出。

```sh
#希望看到屏幕输出，同时将其保存到data.log文件中
lj@Aliyun test % find . -name "*.c" -exec cat {} \; | tee data.log  [0]
/*************************************************************************
	> File Name: a.c
	> Author: Maureen
	> Mail: 1437867946@qq.com
	> Created Time: Sun 27 Sep 2020 04:22:41 PM CST
 ************************************************************************/

#include<stdio.h>

int main() {
    int a;
    scanf("%d", &a);
    printf("a = %d\n", a);
    return 0;
}
#查看data.log中的内容
lj@Aliyun test % cat data.log                                       [0]
/*************************************************************************
	> File Name: a.c
	> Author: Maureen
	> Mail: 1437867946@qq.com
	> Created Time: Sun 27 Sep 2020 04:22:41 PM CST
 ************************************************************************/

#include<stdio.h>

int main() {
    int a;
    scanf("%d", &a);
    printf("a = %d\n", a);
    return 0;
}
```



## 9.10 split 文件切分

语法: `split [-b] <file>  PREFIX`

​		`-b SIZE`: 切分为SIZE大小的文件

​		`-l num`： 以num行为大小切分

```sh
#每三行进行切分,切分结果保存到了以x开头的文件中
lj@Aliyun test % cat data.log | split -l 3                          [0]
lj@Aliyun test % ls                                                 [0]
data.log  xaa  xad  xag  xaj  xam  xap  xas
xab  xae  xah  xak  xan  xaq  xat
xac  xaf  xai  xal  xao  xar
lj@Aliyun test % cat xaa                                            [0]
/*************************************************************************
	> File Name: a.c
	> Author: Maureen
lj@Aliyun test % cat xab                                            [0]
	> Mail: 1437867946@qq.com
	> Created Time: Sun 27 Sep 2020 04:22:41 PM CST
 ************************************************************************/
 #每1k进行切分
 lj@Aliyun test % ls -alh data.log                                   [0]
-rw-rw-r-- 1 lj lj 1.5K Oct  2 07:31 data.log
lj@Aliyun test % cat data.log | split -b 1k
lj@Aliyun test % ls                                                 [0]
data.log  xaa  xab
```



## 9.11 xargs 参数代换

语法：`xargs [-0pne] <command>`

​		`-0`: 将特殊字符还原为普通字符

​		`-eEOF`: 当xargs读到EOF时停止

​		`-p`: 执行命令前询问

​		`-n num`: 每次执行command时需要的参数个数

用法：将前一个命令的标准输出作为后一个命令的参数

```sh
#ls不接收标准输入，但是需要参数，于是使用xargs将前一个命令的标准输入结果拿出来作为ls的参数【使用xargs做参数代换】
lj@Aliyun test % echo "/etc" | xargs ls                             [0]
adduser.conf		       mime.types
adjtime			       mke2fs.conf
alternatives		       modprobe.d
apm			       modules
```

```sh
#获取/etc/passwd中10~20行的数据并用id命令显示，id命令每次只能处理一个，且接收的参数只能是用户名，所以要进行切分
lj@Aliyun test % cat /etc/passwd | head -n 20 | tail -n 10 | cut -d : -f 1 | xargs -n 1 id
uid=10(uucp) gid=10(uucp) groups=10(uucp)
uid=13(proxy) gid=13(proxy) groups=13(proxy)
uid=33(www-data) gid=33(www-data) groups=33(www-data)
uid=34(backup) gid=34(backup) groups=34(backup)
uid=38(list) gid=38(list) groups=38(list)
uid=39(irc) gid=39(irc) groups=39(irc)
uid=41(gnats) gid=41(gnats) groups=41(gnats)
uid=65534(nobody) gid=65534(nogroup) groups=65534(nogroup)
uid=100(systemd-network) gid=102(systemd-network) groups=102(systemd-network)
uid=101(systemd-resolve) gid=103(systemd-resolve) groups=103(systemd-resolve)
```

```sh
# 将/etc/passwd中sshd以前的结果用id命令打印出来，-esshd指定结束符为sshd
lj@Aliyun test % cat /etc/passwd | cut -d : -f 1 | xargs -n 1 -esshd id
uid=0(root) gid=0(root) groups=0(root)
uid=1(daemon) gid=1(daemon) groups=1(daemon)
uid=2(bin) gid=2(bin) groups=2(bin)
uid=3(sys) gid=3(sys) groups=3(sys)
uid=4(sync) gid=65534(nogroup) groups=65534(nogroup)
uid=5(games) gid=60(games) groups=60(games)
uid=6(man) gid=12(man) groups=12(man)
uid=7(lp) gid=7(lp) groups=7(lp)
uid=8(mail) gid=8(mail) groups=8(mail)
uid=9(news) gid=9(news) groups=9(news)
uid=10(uucp) gid=10(uucp) groups=10(uucp)
uid=13(proxy) gid=13(proxy) groups=13(proxy)
uid=33(www-data) gid=33(www-data) groups=33(www-data)
uid=34(backup) gid=34(backup) groups=34(backup)
uid=38(list) gid=38(list) groups=38(list)
uid=39(irc) gid=39(irc) groups=39(irc)
uid=41(gnats) gid=41(gnats) groups=41(gnats)
uid=65534(nobody) gid=65534(nogroup) groups=65534(nogroup)
uid=100(systemd-network) gid=102(systemd-network) groups=102(systemd-network)
uid=101(systemd-resolve) gid=103(systemd-resolve) groups=103(systemd-resolve)
uid=102(syslog) gid=106(syslog) groups=106(syslog),4(adm)
uid=103(messagebus) gid=107(messagebus) groups=107(messagebus)
uid=104(_apt) gid=65534(nogroup) groups=65534(nogroup)
uid=105(uuidd) gid=109(uuidd) groups=109(uuidd)
uid=106(ntp) gid=111(ntp) groups=111(ntp)
```

## 9.12 求字符串中的数字和

### 使用tr命令和$[]运算

```sh
#1、将不是0~9的字符替换为空格
lj@Aliyun test % echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -c "0-9" " "
1 2 3 4 5 6 7 9               8 12    234 %
#2、对空格进行压缩
lj@Aliyun test % echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " "
1 2 3 4 5 6 7 9 8 12 234 %
# 3、将空格替换为+号
lj@Aliyun test % echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " " | tr " " "+"
1+2+3+4+5+6+7+9+8+12+234+%
#4、使用$[]进行计算，在最后加了一个0，是因为最后多了个+号 （在bash下可正确执行）
lj@Aliyun:~/test$ echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " " | echo $[ `tr " " "+"`0]
291
```

或：

```sh
#1、将字符串中非0~9的替换为空格
lj@Aliyun test % echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " "      [0]
1 2 3 4 5 6 7 9 8 12 234 %  
#2、抹去最后的空格（！！很精妙），xargs提取出标准输入中的值
lj@Aliyun test % echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " " | xargs
1 2 3 4 5 6 7 9 8 12 234
#3、将空格替换为+号
lj@Aliyun test % echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " " | xargs   | tr " " "+"
1+2+3+4+5+6+7+9+8+12+234
#4、将式子放到bc计算器中计算
lj@Aliyun test % echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " " | xargs   | tr " " "+" | bc
291
```

可以将上面的使用bc计算器计算的操作替换为如下：

```sh
lj@Aliyun test % echo $[`echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " " | xargs   | tr " " "+" `]
291
```

### 使用shell脚本

```sh
#直接在终端中写shell脚本
lj@Aliyun test % sum=0                                                [0]
lj@Aliyun test % for i in `echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " " `;do           [0]
for> sum=$[ $sum + $i]
for> done
lj@Aliyun test % echo $sum                                                      [0]
291
```

![image-20201002084440105](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201002084440105.png)或：

编写shell脚本

```sh
#sum.sh
#!/bin/bash
sum=0
nums=`echo "1 2 3 4 5 6 7 9 a v 你好 . /8 12 abc234" | tr -s -c "0-9" " "`
for i in $nums;do
    sum=$[ $sum + $i ]
done
echo $sum
#给sum.sh添加可执行权限
lj@Aliyun test % chmod +x sum.sh
#执行sum.sh
lj@Aliyun test % ./sum.sh                                      [0]
291
```

 `$[]`计算整数值的用法可见<u>5.4: 附录1：shell元字符</u>



# 十、Shell编程基础

第一个shell脚本

```shell
#!/bin/bash
echo 'Hello HaiZei'  #这是注释
```

其中`#!/bin/bash`必须这样写，告诉计算机应该用哪个解释器来解释接下来的语言。

**常见面试题**：当在终端输入`x`之后，发生了什么事情？（数据的操作经过，从键盘开始->....->服务器->.....）

`$变量名`：表示取某个变量的值。

通常执行shell脚本有两种方式：（例脚本名为first.sh）

```sh
1、bash first.sh
2、chmod +x first.sh
   ./first.sh
```

第2种方式是通过读取程序中的第一行找到指定的解释器来解释。

另外还有一种方式：

```sh
source first.sh
```

虽然脚本也执行了，但是source是在当前环境下执行，没有开子进程；而另外两种方式都是开了子进程执行。

## 10.1  变量与局部变量

- 变量的定义

    shell是弱类型语言，即没有类型区分。

    - a=12 
    - a=helloworld
    - a=\`pwd\`     (输出pwd的值放到a中，\`\`是命令替换符)
    - a=`$a:a`     (a是取出变量a的值，然后加上a字符，就是字符串拼接，这是bash语法，zsh中需要将变量用{}括起来，用来界定​的取值范围)

    ```sh
    lj@Aliyun test % a=123                                                                                         
    lj@Aliyun test % echo $a                                                                                       
    123
    ```

    赋值语句中不能包含空格，`a = 123`会被解析成`a`是个命令，`=`和`123`都是它的参数。

    ```sh
    lj@Aliyun test % a=`pwd`                                                                                       
    lj@Aliyun test % echo $a                                                                                  
    /home/lj/test
    lj@Aliyun test % a=${a}:a                                                                                     
    lj@Aliyun test % echo $a                                                                                       
    /home/lj/test:a
    ```

- 局部变量

    - local  a=12

## 10.2 特殊变量

### 10.2.1 位置变量

- `$0`：获取当前执行shell脚本的文件名，包括路径。（即第一个参数）
- `$n`：获取当前执行脚本的第n个参数，n=1...9，如果n大于9，则需要将n使用大括号括起来；
- `$*`：获取当前shell的所有参数，将所有命令行参数视为单个字符串，相当于"`$1$2$3`";
- `$#`：得到执行当前脚本的参数个数；
- `$@`：获取这个程序所有参数，并保留参数之间的任何空白，相当于"`$1`" "`$2`" "`$3`"，这是将参数传给其他程序的最好办法；

```shell
#!/bin/bash
echo "argv[0] = $0"
echo "argv[1] = $1"
echo "argv[2] = $2"
echo "argv[3] = $3"

echo "\$# = $#"
echo "\$* = $*"
echo "\$@ = $@"
```

执行结果：

```sh
lj@Aliyun test % bash 2.arg.sh a b c d                                                                         
argv[0] = 2.arg.sh
argv[1] = a
argv[2] = b
argv[3] = c
$# = 4          #只计算参数个数，文件名不会包含
$* = a b c d
$@ = a b c d
```

### 10.2.2 状态变量

- `$?`：判断上一指令是否成功执行，0为成功，非零为不成功
- `$$`:   取当前进程的PID
- `$!`：上一个指令的PID

```sh
lj@Aliyun test % ls                                                                             2.arg.sh  3.c  a  a.c  a.out  b.c  c.c  data.log  first.sh  ls.log  sum.sh
lj@Aliyun test % echo $?                                                                       
0  #ls命令的执行结果  
```



## 10.3 变量，参数展开

- `${parameter:-word}`：如果变量未定义，则表达式的值为word。

    ```sh
    #如果Dir1变量不不存在，那么该表达式的值为/tmp
    lj@Aliyun test % echo ${Dir1:-"/tmp"}                                                                         
    /tmp
    #Dir的值还是空的
    lj@Aliyun test % echo ${Dir}                                                                                   
    
    ```

- `${parameter:=word}`:   如果变量未定义，则设置变量的值为word，返回表达式的值也是word。

    ```sh
    lj@Aliyun test % echo ${Dir1:="/tmp"}                                                                         
    /tmp
    lj@Aliyun test % echo ${Dir1}                                                                                
    /tmp
    ```

- `${parameter:?word}`:   用于捕捉由于变量未定义而导致的错误并退出程序。

    ```sh
    #如果Dir2未定义，输出Don't define，退出程序
    lj@Aliyun test % echo ${Dir2:?"Don't define"}                                                                
    zsh: Dir2: "Don't define"
    ```

- `${parameter:+word}`：如果变量已经定义，返回word，也就是真。

    ```sh
    #如果变量Dir1存在,则输出Exist,表达式不加冒号也是可以的
    lj@Aliyun test % echo ${Dir1:+"Exist"}                                                                         
    Exist
    ```

- `${!prefix*}`：叹号! 是前缀匹配，匹配prefix开头的变量

- `${!prefix@}`：prefix开头的变量

```sh
#使用bash
lj@Aliyun:~/test$ abc=123
lj@Aliyun:~/test$ abcd=1
lj@Aliyun:~/test$ abcrr=1
lj@Aliyun:~/test$ echo ${!abc*}
abc abcd abcrr
lj@Aliyun:~/test$ echo ${!abc@}
abc abcd abcrr
```

实例：

```sh
#Dir是个变量，删除Dir变量的值的目录下的压缩文件。如果Dir不存在，那么该操作就会在当前目录下执行
find ${Dir} -name "*.gz" -type f | xargs rm -rf
#更改为更为安全的方式
find ${Dir?"Not Found"} -name "*.gz" -type f | xargs rm -rf
```

```sh
rm -rf ${Dir}/*
```

如果Dir不存在，那么该命令就相当于是

```sh
rm -rf /*
```

问题就很严重了。

## 10.4 字符串展开

### 10.4.1 字符串的截取与删除

- `${#parameter}`：输出字符串的长度

    ```sh
    lj@Aliyun test % echo ${HOME}                                                                /home/lj
    lj@Aliyun test % echo ${#HOME}                                                             8
    lj@Aliyun test % printf $HOME                                                               /home/lj
    ```
    
- `${parameter:offset}`：从第offset字符开始截取

    ```sh
    #从第6个字符开始截取
    lj@Aliyun test % printf ${HOME:6}                                                            lj
    ```
    
- `${paramter:offset:length}`：从offset字符开始截取，取length长度

    ```sh
    #从第2个字符开始截取，取4个字符长度
    lj@Aliyun test % printf ${HOME:2:4}                                                          ome/
    ```
    
- `${paramter#pattern}`：从头删除最短匹配

    ```sh
    #从头删除abcd
    lj@Aliyun test % A=abcd1234                                                                  lj@Aliyun test % echo ${A#abcd}                                                             1234
    ```
    
- `${parameter##pattern}`：最长

    ```sh
    lj@Aliyun test % A=abcabcdabc123
    lj@Aliyun test % echo ${A##abc}                                                                               
    abcdabc123
    ```

- `${parameter%pattern}`：从尾删除最短 

    ```sh
    #从尾删除CDD
    lj@Aliyun test % A=ABCDeeeABCDD
    lj@Aliyun test % echo ${A%CDD}                                                             ABCDeeeAB
    ```

- `${patameter%%pattern}`：从尾删除最长

    ```sh
    lj@Aliyun test % A=ABCDeeeABCDD
    lj@Aliyun test % echo ${A%%ABCDD}                                                           ABCDeee
    ```

### 10.4.2 字符串的替换

- `${parameter/pattern/string}`:   第一个匹配被替换

    ```sh
    #第一个匹配的abc被替换为123
    lj@Aliyun test % A=abcabc                                                                    lj@Aliyun test % echo ${A/abc/123}                                                          123abc
    lj@Aliyun test % A=aabcabc                                                                 lj@Aliyun test % echo ${A/abc/123}                                                          a123abc
    ```
    
- `${parameter//pattern/string}`： 全部匹配被替换

    ```sh
    lj@Aliyun test % A=abcabc                                                                   lj@Aliyun test % echo ${A//abc/123}                                                         123123
    ```
    
- `${parameter/#pattern/string}`：字符串开头的替换

    ```sh
    #字符串开头的World替换为Hello
    lj@Aliyun:~/test$ A=WorldWorld
    lj@Aliyun:~/test$ echo ${A/#World/Hello}
    HelloWorld
    ```

- `${parameter/%pattern/string}`：字符串结尾的替换

    ```sh
    #字符串结尾的World替换为Hello
    lj@Aliyun:~/test$ A=WorldWorld
    lj@Aliyun:~/test$ echo ${A/%World/Hello}
    WorldHello
    ```

- `${parameter,,} ${parameter^^}`： 全部转换为小写、大写

    ```sh
    #全部转换为大写
    lj@Aliyun:~/test$ A=aabcabc
    lj@Aliyun:~/test$ echo ${A^^}
    AABCABC
    #全部转换为小写
    lj@Aliyun:~/test$ A=AbcABC
    lj@Aliyun:~/test$ echo ${A,,}
    abcabc
    ```

- `${parameter,} ${parameter^}`：首字母转换为小写、大写

    ```sh
    #首字母转换为小写
    lj@Aliyun:~/test$ A=Abcabc
    lj@Aliyun:~/test$ echo ${A,}
    abcabc
    #首字母转换为大写
    lj@Aliyun:~/test$ A=abcABC
    lj@Aliyun:~/test$ echo ${A^}
    AbcABC
    ```

shell中声明的变量存储在当前进程池中。

## 10.5 输入输出

### 10.5.1 输入 - read

- `read [-options]  [variable...]`
    - `-a array`         #把输入赋值到数组array中，从索引号零开始。
    - `-d delimiter`  #用字符串delimiter 中的第一个字符指示输入结束，而不是一个换行符
    - `-e`                #使用Readline来处理输入。这使得与命令行相同的方式编辑输入
    - `-n num`         #读取num个输入字符，而不是整行
    - `-p prompt`  #为输入显示提示信息，使用字符串prompt
    - `-r`                   #Raw mode，不把反斜杠字符解释为转义字符
    - `-s`                  #Silent mode
    - `-t seconds`   #超时
    - `-u  fd`            #使用文件描述符 fd 中的输入，而不是标准输入

```sh
#读取一个值
lj@Aliyun test % read name   #输入的命令                                                          lj   #输入的值
lj@Aliyun test % echo ${name}                                                                    lj
```

```sh
#读取多个值
lj@Aliyun test % read name age address        #输入的命令                                          maureen 18 shenzhen  #输入的值
lj@Aliyun test % echo $name $age $address                                                        maureen 18 shenzhen
```

```sh
#为输入显示提示信息
lj@Aliyun:~/test$ read -p "please input your password:"
please input your password:12334  #12334为用户输入的密码，会显示

#不显示输入的密码，使用-s
lj@Aliyun:~/test$ read -s  -p "please input your password:"
please input your password:   #用户输入密码，但是密码不会显示

#设置超时时间，如果1s不输入密码就退出程序（-t 1）
lj@Aliyun:~/test$ read -s -t 1 -p "please input your password:"
please input your password:lj@Aliyun:~/test$
```



### 10.5.2  输出 - echo

- `echo string`
    - `echo -e   "Hello HaiZei\n"`  #开启转义
    - `echo "Hello $name, This is HaiZei"`
    - echo " \\"Hello HaiZei\\" "

```sh
lj@Aliyun:~/test$ echo "Hello\n"
Hello\n
#echo -n 不输出默认换行
lj@Aliyun:~/test$ echo -n "Hello\n"  
Hello\nlj@Aliyun:~/test$
#echo -e 开启转义
lj@Aliyun:~/test$ echo -e "Hello\n"
Hello

lj@Aliyun:~/test$ echo "\"hello\""
"hello"
```

### 10.5.3 输出 - printf

- `printf  format-string  [arguments...]`，类似于C语言的用法

```sh
lj@Aliyun:~/test$ printf "%s is %d years old\n" "lj" "18"
lj is 18 years old
```

## 10.6 函数

函数的三种写法：

```shell
#!/bin/bash
function _printf_ {
	echo $1
	return
}

_printf_() {
	echo $1
	return 
}

function _printf_() {
	echo $1
	return
}
```

函数使用功能方法：

```shell
_printf_ "Hello World"
```

因为`$1`是第一个参数，所以调用的时候要传入参数。传参用空格隔开，函数调用其实就相当于执行命令。



```sh
#!/bin/bash
function _print_ {
    echo $1
    return
}

_print_ "Maureen is 18 years old" #函数调用，因为函数中有$1使用第一个参数，所以要传入参数
```

运行：

```sh
lj@Aliyun test % bash 3.function.sh                                                                               
Maureen is 18 years old
```

或者：

```sh
lj@Aliyun test % _print_ abc                                                                                     
zsh: command not found: _print_   #系统中是没有_print_命令的
lj@Aliyun test % source 3.function.sh     #使用source可以使得环境变量保存在当前环境中                                  
Maureen is 18 years old
lj@Aliyun test % _print_ abc                                                                                     
abc
```



## 10.7 流程控制

### 10.7.1 if

```shell
#!/bin/bash
if [[ condition ]]; then
    #statements
fi

if [[ condition ]]; then
    #statements
    else
    #statements
fi

if [[ condition ]]; then
    #statements
elif [[ condition ]]; then
    #statements
elif [[ condition ]]; then
    #statements
    else
    #statements
fi
i
```

`[[ condition ]]`是test表达式，中括号中condition两侧都是有空格的。

实例：

```shell
#!/bin/bash
#如果不传入参数，默认是0
age=$1
function _print_ {
    echo $1
    return
}

#可以使用man test查看test表达式中应该使用的写法
if [[ age -gt 18 ]]; then
    echo ">18"
elif [[ age -le 18 ]]; then
        echo "<=18"
fi
```

运行：

```sh
lj@Aliyun test % bash 3.fun.sh 18                                                                                  <=18
lj@Aliyun test % bash 3.fun.sh 20                                                                                  >18
lj@Aliyun test % bash 3.fun.sh 25                                                                                  >18
```



### 10.7.2 while

```shell
#!/bin/bash
while [[condition ]]; do
    #statements
done
```

实例：

```shell
#!/bin/bash
#从100输出到0
num=100
#如果num >=0
while [[ $num -ge 0 ]]; do
    echo ${num}
    num=$[ ${num} - 1 ]
done
```



### 10.7.3 for

```shell
#!/bin/bash
for i in words; do
    #statements
done

for (( i = 0; i < 10; i++ )); do
    #statements
done
```

实例：输出100到0，for的两种写法

```sh
#!/bin/bash
for (( i = 0; i <= 100; i++ )); do
    echo ${i}
done

#seq是序列，0到100
for i in `seq 0 100`;do
    echo $i
done
```



### 10.7.4 until

```shell
#!/bin/bash
until [[ condition ]]; do
    #statements
done
```

实例：输出0到100

```shell
#!/bin/bash
sum=0
until [[ ${sum} -gt 100 ]];do
    echo $sum
    sum=$[ $sum + 1 ]
done
```

### 10.7.5 case

```shell
#!/bin/bash
case word in
    pattern )
        ;;
esac
```

实例：

```shell
#!/bin/bash
read age
case $age in
    1 )
        echo "1"
        ;;
    2 )
        echo "2"
        ;;
esac
```



## 10.8 数组

### 10.8.1 数组声明与赋值

- `declare -a a`  #数组声明，可以不用声明
    - `name[subscript]=value` #数组赋值
    - ``name=(value1 value2 ...)` #数组赋值

```sh
lj@Aliyun test % name=(maureen1 maureen2)                                                                         
lj@Aliyun test % echo ${name[1]}                                                                                 
maureen1
lj@Aliyun test % name[2]=maureen3     #给数组赋值                                                                            
lj@Aliyun test % echo ${name[2]}                                                                                 
maureen3
```



### 10.8.2 数组操作

- 输出数组内容
    - `${array[*]}`

    - `${array[@]}`

        ```sh
        lj@Aliyun:~/test$ arr=(test0 test1 test2) #给数组赋值
        lj@Aliyun:~/test$ arr[3]=test3 #给数组赋值
        lj@Aliyun:~/test$ echo ${arr[*]}
        test0 test1 test2 test3
        lj@Aliyun:~/test$ echo ${arr[@]}
        test0 test1 test2 test3
        ```

- 确定数组元素个数
    - `${#array[@]}`

        ```sh
        #操作接上步
        lj@Aliyun:~/test$ echo ${#arr[@]}
        4
        ```

- 找到数组的下标
    - `${!array[@]}`

        ```sh
        #操作接上步
        lj@Aliyun:~/test$ echo ${!arr[@]}
        0 1 2 3
        lj@Aliyun:~/test$ arr[100]=maureen
        lj@Aliyun:~/test$ echo ${!arr[@]}
        0 1 2 3 100  #不需要下标连续
        ```

- 数组追加
    - `array+=(a b c)`

        ```sh
        #操作接上步
        lj@Aliyun:~/test$ arr+=(1 2 3)
        lj@Aliyun:~/test$ echo ${arr[*]}
        test0 test1 test2 test3 maureen 1 2 3
        ```

- 数组排序
  
- `sort` ：利用管道就可以排
  
- 删除数组与元素
    - `unset`

        ```shell
        lj@Aliyun:~/test$ echo ${!arr[*]}
        0 1 2 3 100 101 102 103
        lj@Aliyun:~/test$ unset arr[100] #删除arr[100]
        lj@Aliyun:~/test$ echo ${!arr[*]}
        0 1 2 3 101 102 103
        lj@Aliyun:~/test$ echo ${arr[100]} #结果为空
        
        lj@Aliyun:~/test$ unset arr #删除整个数组
        lj@Aliyun:~/test$ echo ${!arr[*]}
        
        ```

### 10.8.3 shell实现线性筛

> 求一定范围内的素数和。
>
> 采用<span style="color:red">线性筛实现</span>

1、传入两个参数

​	1） 第一个为起始数字<span style="color:red">`start_num`</span>（包含该数字）

​	2） 第二个为终止数字<span style="color:red">`end_num`</span>(包含该数字)

2、如果<span style="color:red">`start_num`</span>小于 0，则起始数从 0 开始

3、输出该范围内的所有<span style="color:red">`素数的和`</span>

4、使用方式<span style="color:red">`bash Prime.sh 0 100`</span>

自己实现的版本：

```shell
#!/bin/bash

start_num=$1
end_sum=$2
sum=0

if [[ ${start_num:-"undefined"} = "undefined" ]]; then
    echo ${start_num:?"error:Please specified start_num"}
elif [[ ${end_sum:-"undefined"} = "undefined" ]]; then
    echo ${end_sum:?"error:Please specified end_sum"}
fi

if [[ $start_num -lt 0 ]]; then
    start_num=0
fi

#数组声明与赋值
declare -a prime
for (( i = 2; i <= ${end_sum}; i++ )); do
    prime[$i]=0
done

for (( i = 2; i <= ${end_sum}; i++ )); do
    if [[ ${prime[$i]} -eq 0 ]]; then
        prime[0]=$[ ${prime[0]} + 1 ]
        prime[${prime[0]}]=$i
        if [[ $i -ge ${start_num} ]];then
        	sum=$[ $sum + i]
        fi
    fi

    for (( j = 1; j <= ${prime[0]}; j++ )); do
        tmp1=$[ prime[$j] * i]
        if [[ tmp1 -gt $end_sum ]]; then
            break
        fi
        tmp=$[ prime[$j] * i]
        prime[$tmp]=1
       #echo "second for:prime[$j]=${prime[$j]}"
        tmp2=$[i % prime[$j]]
        if [[ tmp2 -eq 0 ]]; then
            break
        fi
    done
done

printf "prime sum is %d" "$sum"
```

老师版本：

```shell
#!/bin/bash
declare -a prime #定义数组，也可不定义
sum=0

function usage() {
    printf "Usage : %s start_num end_num\n" $0 #$0是usage函数的参数,前面有几个占位符，后面就有几个参数
}

function init() { #初始化数组, S和E为数组的下标
    S=$1
    E=$2
    for (( i = $S; i<=$E; i++ ));do #将数组从S到E初始化为0，不用从0开始初始化
        prime[$i]=0
    done
}

#如果参数的个数不等于2，直接退出, $#获取参数的个数
if [[ $# -ne 2 ]]; then
    usage
    exit
fi

start_num=$1
end_num=$2

#如果start_num小于0
if [[ $start_num -lt 0 ]];then
    start_num=0
fi

#如果start_num大于end_num
if [[ ${start_num} -gt ${end_num} ]];then
    usage
    exit
fi

init 0 ${end_num} #调用init函数初始化数组

#线性筛的实现
for (( i = 2; i <= ${end_num}; i++ ));do
    if [[ ${prime[$i]} -eq 0 ]];then
        prime[0]=$[ ${prime[0]} + 1 ]
        prime[${prime[0]}]=$i
        if [[ $i -ge ${start_num} ]];then #从start_num开始计算
            sum=$[ ${sum} + $i ]
        fi
    fi
    for (( j=1; j<= ${prime[0]}; j++ ));do
        if [[ $[ ${i} * ${prime[$j]} ] -gt ${end_num} ]];then
            break
        fi
        prime[$[ ${i} * ${prime[$j]} ]]=1
        if [[ $[${i} % ${prime[$j]}] -eq 0 ]];then
            break
        fi
    done
done

echo $sum
```

```sh
bash -x prime.sh 5 1 //可以将中间信息打印出出来
```



# 十一、用户管理

## 11.1  用户管理的重要配置文件

| 配置文件     | 内容                                                         |
| ------------ | ------------------------------------------------------------ |
| /etc/passwd  | 用户名      密码位     用户编号      归属组编号      姓名     $HOME     $SHELL |
| /etc/shadow  | 用户名      已加密密码   密码改动信息   密码策略             |
| /etc/group   | 群组名      密码位    群组编号    组内用户                   |
| /etc/gshadow | 群组密码相关文件                                             |
| /etc/sudoers | 用户名   权限定义   权限 （sudo)                             |

`/etc/passwd`中保存密码不安全，所以真正的密码放在了`/etc/shadow`中，而在`/etc/passwd`中密码位使用`x`来占位。

`/etc/sudoers`中保存了能执行`sudo`命令的用户。

### 11.1.1 /etc/passwd文件说明

![image-20201012123612438](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201012123612438.png)

| root     | x    | 0    | 0    | root     | /root | /bin/bash |
| -------- | ---- | ---- | ---- | -------- | ----- | --------- |
| 账号名称 | 密码 | uid  | gid  | 用户信息 | $HOME | $SHELL    |



### 11.1.2 /etc/shadow文件说明

![image-20201012123959844](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201012123959844.png)

| root     | $6$...1      | 18515          | 7                | 90                     | 7                      | null               | null         | null |
| -------- | :----------- | -------------- | ---------------- | ---------------------- | ---------------------- | ------------------ | ------------ | ---- |
| 账户名称 | 加密过的密码 | 修改密码的日期 | 密码不可改动时间 | 密码需要重写修改的时间 | 密码变更期限前警告时间 | 密码过期的宽限时间 | 账号失效日期 | 保留 |

22端口是sshd默认端口，保证安全可以改端口。



### 11.1.3 /etc/group文件说明

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201012124906335.png" alt="image-20201012124906335" style="zoom:50%;" />

| Test | x        | 1002 | userA, userB      |
| ---- | -------- | ---- | ----------------- |
| 组名 | 群组密码 | gid  | 支持的账户 (组员) |



### 11.1.4 /etc/gshadow文件说明

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201012125053211.png" alt="image-20201012125053211" style="zoom:50%;" />

| Test | ！   | null       | userA, userB         |
| ---- | ---- | ---------- | -------------------- |
| 组名 | 密码 | 群组管理员 | 加入该群组的所属账号 |

`!`：表示组的密码大多时候是空的。



### 11.1.5 /etc/sudoers文件说明

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201012125502413.png" alt="image-20201012125502413" style="zoom:50%;" />

系统中，有两个组是由管理员权限的，admin和sudo。

```shell
#将userA加到sudo用户组中
usermod -G sudo userA
```



## 11.2 用户管理相关的命令

| 命令    | 说明                | 命令    | 说明               |
| ------- | ------------------- | ------- | ------------------ |
| su      | 切换用户            | sudo    | 临时切换为root用户 |
| passwd  | 设定用户密码        | gpasswd | 设定群组密码       |
| chsh    | 更改用户shell       | usermod | 修改用户账号       |
| useradd | 新建用户（adduser） | userdel | 删除用户           |
| id      | 显示用户信息        | ...     | ...                |

### 11.2.1 su 切换用户

- `su [-lmpfc] <username>`
    - `-` | `-l` : 重新登录
    - `-m` | `-p`： 不更改环境变量
    - `-c command`： 切换后执行命令，并退出

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201012130823172.png" alt="image-20201012130823172" style="zoom:50%;" />

### 11.2.2 sudo 临时切换到root

- `sudo [-siul] <command>`
    - `-s`: 切换为root shell
    - `-i`: 切换到root shell，并初始化
    - `-u username|uid` : 执行命令的身份
    - `-l`: 显示自己的权限

```shell
sudo -i #切换到root shell
sudo reboot #以管理员身份执行reboot命令
```



### 11.2.3 passwd 设定用户密码

- `passwd [-dleSxnf] <username>`
    - `-d` : 清除密码
    - `-l`：锁定账户
    - `-e`：使密码过期
    - `-S`: 显示密码认证信息
    - `-x days`：密码修改后最大使用天数
    - `-n days`:  密码修改间隔时间
    - `-f`: 更改用户信息（用户昵称）
    - `-i`: 密码过期后宽限时间

### 11.2.4 gpasswd 设置群组及群组密码

- `gpasswd [-adrAM] <群组名>`
    - `-a (add)  username` : 将用户加入群组
    - `-d (delete)  username`：将用户从群组中删除
    - `-r`: 删除密码
    - `-A (admin)  username`: 将用户设置为群组管理员
    - `-M  username1，username2 ...`: 设置群组成员



### 11.2.5 chsh更改用户shell

`chsh -s SHELL <username>` : 如果不加用户，就默认修改当前用户的shell

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201012125905861.png" alt="image-20201012125905861" style="zoom:50%;" />



### 11.2.6 useradd 添加用户

- `useradd [-dmMsugGnefcD] <username>`
    - `-d dir`: 指定`$HOME`
    - `-m`: 自动建立`$HOME`(/home/${username})
    - `-M`: 不自动建立`$HOME`
    - `-s shell`: 设置用户登录shell
    - `-u uid`: 设置用户编号 （一般从1000开始默认自增）
    - `-g groupname`: 设定用户归属群组
    - `-G groupname`: 设置用户归属附加群组 
    - `-n`： 不建立以用户名称为群组名称的群组
    - `-e days`: 设置账号过期时间，绝对时间
    - `-f days`：缓冲时间，days天后关闭账号
    - `-c string`: 设置用户备注
    - `-D [表达式]`：更改预设值
- `/etc/login.defs`： 新建用户规则
- `/etc/skel`/: 新建用户默认文件

### 11.2.7 userdel 删除用户

- `userdel -r <username>`
    - `-r`: 删除用户相关文件和目录（邮件，家目录）



### 11.2.8 usermod命令

- `usermod [-cdefgGlLsuU] <username>`
    - `-c string`: 修改备注信息
    - `-d dir`: 修改`$HOME`
    - `-e days`: 账户失效日期 YY-MM-DD
    - `-f days`: 修改密码后宽限的日期
    - `-g groupname`: 修改用户所属群组
    - `-G groupname`: 修改用户所属附加群组
    - `-l username`: 修改用户账号名称
    - `-L`:  锁定用户密码，使密码无效
    - `-s shell`: 修改用户登录后所使用的的shell
    - `-u uid`: 修改用户ID
    - `-U`: 解除密码锁定

### 11.2.9 id 命令

- `id [-gGnru] <username>`
    - `-g`: 下属所属组ID
    - `-G`: 显示附加组ID
    - `-n`: 显示用户，所属组名，或附加群组的名称
    - `-u`: 显示用户ID
    - `-r`: 显示实际ID

### 11.2.10 随堂练习

- 新建一个用户Admin
    - 密码100天后过期，提前7天提醒，过期10天后不修改密码将关闭账号
    - 定义SHELL， 有HOME
    - 登录打印自定义欢迎信息：Welcome Admin (此处取变量)！Today is 2017-07-27
        - 并且打印最近一次登录的详细信息和近期登录总次数
    - ~~（可直接执行my_ls)~~
    - 可执行sudo命令

# 十二、进程管理 

| 命令   | 说明                      | 命令  | 说明                                  |
| ------ | ------------------------- | ----- | ------------------------------------- |
| free   | 打印系统情况和内存情况    | top   | 显示当前系统进程情况，内存，CPU等信息 |
| dstat  | 实时监控磁盘，CPU，网络等 | ps    | 报告当前进程状态                      |
| pstree | 以树状显示进程派生关系    | pgrep | 查找进程ID                            |
| kill   | 删除执行中的程序和工作    | pkill | 批量按照进程名杀死进程                |

## 12.1 free 打印系统情况和内存情况

- free [-bkmgotsh]
    - -b | k | m | g：以字节，KB，M，G显示
    - -o：忽略缓冲区调节列
    - -t seconds：每隔seconds 执行一次
    - -h：以可读形式显示

![image-20201015125615065](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015125615065.png)



```shell
free -h -t 5 #每5s执行一次
#等价于
watch free -h #默认情况每2s执行一次free -h
watch -n 5 free -h #设置每5s执行一次
```



## 12.2 top 显示当前系统进程情况，内存，CPU等信息

孤儿进程：子进程一出生，父亲就死了，由1号进程（systemd)收养。

僵尸进程：子进程死了，父进程没有给它收尸。

- top [-bcdsSupng]
    - -b: 以批处理模式操作
    - -c：显示完整的命令
    - -d seconds: 屏幕刷新间隔时间
    - -s：以安全模式运行
    - -S：累积模式
    - -u uname: 执行username
    - -p pid：指定PID
    - -n nums：循环显示次数
    - -q：root时，给尽可能高的优先级

![image-20201015130744936](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015130744936.png)

## 12.3 dstat 实时监控磁盘，CPU,网络等

### 12.3.1 dstat

- dstat
- dstat 2 :每2s一次
- dstat 2 10 ： 每2s一次，输出10次
- dstat -list：
- dstat 2 10 -output /tmp/data.csv

![image-20201015131211906](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015131211906.png)



| usr    | sys    | idl  | wai                              |
| ------ | ------ | ---- | -------------------------------- |
| 用户态 | 内核态 | 空闲 | 通常压力测试等待资源的时候才会有 |

### 12.3.2 nmon

另外有款软件：nmon，也是用于系统监测。输入`nmon`命令，在显示的界面输入对应的参数查看想看的部分，c是CPU，m是memory等。如果不存在该软件，可以使用`apt install nmon`安装

![image-20201015131712581](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015131712581.png)

当运行程序：

```C
#include <stdio.h>
int main() {
	while(1) {
	
	}
}
```

的时候，可以看到CPU的user下面显示的是100%，且会在不同的核之间切来切去。通常会问为什么会运行在用户态，为什么会在不同核之间切换以及能够绑定在某个核上运行等问题。

### 12.3.3 htop

还有一个命令：`htop`也可以查看：

![image-20201015132240988](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015132240988.png)

## 12.4 ps 报告当前进程状态

- `ps -aux`
- `ps -ef` :通常配合grep命令进行筛选





## 12.5 pstree 进程的树状结构

- ​	`pstree [-acGhHInpuU]`
    - `-a`: 显示每个程序的完整指令
    - `-n`: 使用PID排序
    - `-p`: 显示pid
    - `-u`: 显示用户名
    - `-l`: 使用长列格式显示树状

![image-20201015133003510](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015133003510.png)



## 12.6 pgrep 查找进程id

- `grep [-onlpgtu] <进程名>`
    - `-o`: 起始进程号
    - `-n`: 结束进程号
    - `-l`:显示进程名称
    - `-P pid`:指定父进程
    - `-g gid`:指定进程组
    - `-t tty`:执行开启的进程终端
    - `-u uid`: 指定uid

![image-20201015133641458](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015133641458.png)

## 12.7 kill 删除执行中的程序和工作

- `kill [-alpsu] <PID>`
    - `-a`: 处理当前进程时，不限制命令名和进程号的对应关系
    - `-l 信号ID`：不加信号ID，则列出全部信号
    - `-p pid`: 给pid的进程只打印相关进程号，而不发送任何信号
    - `-s 信号ID | 信号name`：执行要发出的信号
    - `-u`: 指定用户
    - `kill -9 pid`： 强制杀死pid 
    - `kill pid`

## 12.8 pkill 批量按照进程名杀死进程

- `pkill [-onpgt] <进程名称>`
    - `-o`: 起始pid
    - `-n`: 结束pid
    - `-p pid`: 执行父进程号发送信号
    - `-g`: 指定进程组
    - `-t tty`: 指定终端



# 十三、任务管理

| 命令  | 说明                           |
| ----- | ------------------------------ |
| cron  | 定时任务                       |
| at    | 在指定的时间执行一个指定的任务 |
| sleep | 睡眠                           |

## 13.1 cron 定时任务

- `crontab -e`：编辑

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015135527515.png" alt="image-20201015135527515" style="zoom:50%;" />

- `crontab -l`: 显示列表
- crond为守护进程



## 13.2 at 在指定的时间执行一个指定的任务

单次任务。

- `at [ldc] <args>`
    - `-l`: 列出当前用户的at任务列表，也可以使用atq
    - `-d 任务编号`：删除一个at任务，等同于atrm
    - `-c 任务编号`：显示该任务的实际内存，详情
- 时间指定方式：
    - HH:MM
    - HH:MM YYYY-MM-DD
    - HH:MM[am|pm]  [month]  [date]
    - HH:MM[am|pm] + number[minutes|hours|days|weeks]
    - now + 时间：at now + 2 days
- atd 为at提供守护进程，需要保证atd启动 （守护进程：父进程自杀，被1号进程收养，守护进程一定是孤儿进程）

![image-20201015140705212](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015140705212.png)

上面的操作就是在20:35输出power off到a.log中。（EOT：ctrl+d)

可以使用`tail -f a.log`实时查看文件a.log的内容变化。

# 十四、Linux系统编程

## 14.1 命令行解析

### 14.1.1 getopt函数

- getopt函数：命令行解析函数
    - 头文件：<unistd.h>
    - 原型：`int getopt(int argc, char * const argv[], const char *optstring);`
    - `argc argv`: 由main函数的参数直接传递而来
    - `optstring`: 一个包含准确选项字符的字符串
    - 返回值： 返回下一个选项



### 14.1.2 getopt设置的一些全局变量

- `char *optarg`   -------   指向当前选项参数（如果有）的指针
- `int optind `       -------   再次调用getopt( ) 时的下一个argv 指针的索引
- `int optopt`        ------   最后一个已知选项
- `int opterr`        -------   这个变量非零时，向stderr打印错误。默认为1。

​	

### 14.1.3 参数optstring详解

- getopt( )函数的第三个参数optstring是一个由所有合法的“可选字符”所组成的字符串。
    - 1、单个字符，表示选项
    - 2、单个字符后接一个冒号":"，表示该选项后必须跟一个参数值。参数紧跟在选项后或者以空格隔开。该参数的指针赋给optarg
    - 3、单个字符后跟两个冒号”::"，表示该选项后可以带参数也可以不带。但参数必须紧跟在选项后不能以空格隔开。该参数的指针赋给optarg

例子：”xy:z::“ <span style="color:green">表示x选项没有选项参数;</span><span style="color:cyan">y选项必须有选项参数，中间可有空格可没有;</span><span style="color:red">z参数可有参数选项，也可没有参数选项，但是如果有选项参数的话必须紧跟在选项之后不能有空格</span>



### 14.1.4 getopt函数的通常用法

```C
while ((c = getopt(argc, argv, "xy:z::")) != -1) {
	switch(c) {
		case 'x': ... ...
		case 'y': ... ...
		case 'z': ... ...
		... ...
	}
}
```



### 14.1.5 man查看getopt官方文档

```sh
man 3 getopt
```



### 14.1.6 作业及思考

#### 14.1.6.1、使用getopt示例：实现解析`./a.out -n name -a age -s sex -ttile`选项参数的可执行程序。

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <string.h>


int main(int argc, char **argv) {
    char c;
    char name[20] = {0};
    int age = 0;
    char sex[5] = {0};
    char title[512] = {0};
    while ((c = getopt(argc, argv, "n:a:s:t::")) != -1) {
        switch (c) {
            case 'n': //解析到n选项
                strcpy(name, optarg);
                break;
            case 'a':
                age = atoi(optarg);
                break;
            case 's':
                strcpy(sex, optarg);
                break;
            case 't': //选项后如果有参数必须紧跟选项
                strcpy(title, optarg);
                break;
            default:
                fprintf(stderr, "Usage:%s -n name -s sex -a age -t title!\n", argv[0]);
                exit(1);
        }
    }

    printf("%s is %d years old, %s, with title %s!\n", name, age, sex, title);
    return 0;
}
```

思考：当`-t`选项后如果没有紧跟参数而是与参数间有空格的时候，会出现段错误。那么第25行应该如何修改才能使得不出现段错误而是提示其他信息或者使其也能成功执行？



#### 14.1.6.2、使用`getopt`实现`cat -n`和`cat -b`。

详细说明：参照系统自带的`cat` 实现自己的`cat`命令。

​	1、实现`-b`选项：输出文件，对空行不编号

​	2、实现`-n`选项：输出文件，对所有行编号

​	3、默认情况下：输出文件，不编号

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
//./a.out -b -n file

void cat_file(const char *);
int num = 0;
int b_flag = 0, n_flag = 0;

int main(int argc, char *argv[]) {
    char ch;
    //如果要查看getopt函数文档，两种方式：
    //1、shift + k进入man手册；
    //2、因为安装了ctags，所以使用ctrl + ]进入函数原型，ctrl + o退出函数原型
    while ((ch = getopt(argc, argv, "bn")) != -1) {
        switch (ch) {
            case 'b':
                b_flag = 1;
                break;
            case 'n':
                n_flag = 1;
                break;
            default:
                fprintf(stderr, "Usage : %s [-b|-n] file\n", argv[0]); //argv[0]就是编译好的可执行文件名称
                exit(1);
        }
    }
    //使用方式：./a.out -b -n cat.c a.c
    /*for (int i = 0; i < 5; i++) { //打印命令行输入的参数
        printf("%s ", argv[i]);
    }
    printf("\noptind = %d\n", optind);//optind = 3
    for (int i = optind; i < argc; i++) {
        printf("%s ", argv[i]); //结果就是cat.c和a.c
    }*/
    for (int i = optind; i < argc; i++) { //输出文件操作
        cat_file(argv[i]);
    }
    return 0;
}

void cat_file(const char *file) {
    FILE *fp;
    //下面这行代码将fopen的返回值立即赋值给了fp，所以fp可以不用进行初始化
    //此处有fopen没有fclose是因为程序执行后里面就会被停止，资源会被销毁；
    //但是如果是死循环，就必须要用fclsoe关闭文件，如果同时打开的文件数超过1024，就会出现错误too many opens。
    if ((fp = fopen(file, "r")) == NULL) { 
        //fprintf(stderr, "stderr!\n");
        //perror("fopen()"); //通常使用perror输出错误信息
        perror(file);
        exit(1);
    }
    char buff[1024] = {0}; //buff保存从fp中读取的行数据
    while (fgets(buff, sizeof(buff), fp) != NULL) {
        if (!b_flag && !n_flag) { //没有-b和-n选项，就直接输出
            printf("%s", buff);
            continue;
        }

        if (buff[0] != '\n') { //不为空行
            num++;
            printf("%d\t%s", num, buff);
        } else { //为空行
            if (n_flag && !b_flag) { //只有-n选项，没有-b选项
                num++; //要输出空行行号
                printf("%d\t%s", num, buff);
            } else { //只要-b存在时，就不输出空行的行号（-b -n同时存在时也是不输出空行行号）
                printf("\n");
            }
        }
    }
}
```

==**判断空行**==：通过strlen(buff)的大小可以知道空行的长度为1，但是vim会自动给每一行结束的时候加换行符，通过cat -A可以看到自动加了$;但是如果通过echo的方式写字符到文件中，如果写入1个字符，那么其长度也是为1。所以通过判断strlen(buff)的长度是否为1来判断空行是不行的。于是使用**buff[0] 是否等于 '\n' 来判断是否为空行**。

运行测试如下例子通过：

```sh
./a.out -b cat.c  #空行的行号不会输出
```

```sh
./a.out -n cat.c  #空行的行号也会输出
```

```sh
./a.out -b -n cat.c #空行的行号不会输出
./a.out -bn cat.c #空行的行号不会输出，-bn会被解释为-b -n
```

```sh
./a.out cat.c #原样输出文件
```

对于正在编写的程序，如果要查看函数原型，有如下三种方式：

​		**1、shift + k进入man手册；**

​		**2、因为安装了ctags，所以使用`ctrl + ]`进入函数原型，`ctrl + o`退出函数原型。**

​		**3、`vim -t 函数名`**

总结：

> fgets函数：可以按行读取，
>
> perror函数：输出打印错误信息



## 14.2 文件的打开与读写

见14.1.6.2 `cat -n`和`cat -b`的实现

## 14.3 目录的打开与读取

### 14.3.1 打开目录的函数opendir

打开目录的函数：`opendir`。得到了指针和目录，指针指向一块内存空间，通过指针可以访问这块内存空间。

```sh
NAME #函数名
       opendir, fdopendir - open a directory
SYNOPSIS #概要
       #include <sys/types.h>
       #include <dirent.h>

       DIR *opendir(const char *name);
       DIR *fdopendir(int fd);
  Feature Test Macro Requirements for glibc (see feature_test_macros(7)):

       fdopendir():
           Since glibc 2.10:
               _POSIX_C_SOURCE >= 200809L
           Before glibc 2.10:
               _GNU_SOURCE
DESCRIPTION #描述
       The  opendir()  function  opens  a directory stream corresponding to the directory name, and returns a pointer to the directory stream. #打开了目录名对应的目录流，返回执行目录流的指针
       The stream is positioned at the first entry in the directory.

       The fdopendir() function is like opendir(), but returns a directory stream for the directory referred to by the  open  file  descriptor fd.   After  a  successful  call  to  fdopendir(), fd is used internally by the implementation, and should not otherwise be used by the application.

RETURN VALUE #返回值
       The opendir() and fdopendir() functions return a pointer to the directory stream.  On error, NULL is returned, and errno is set  appropriately. #如果出现错误，返回NULL,对应的erron会被设置

ERRORS #错误信息
       EACCES Permission denied.

       EBADF  fd is not a valid file descriptor opened for reading.

       EMFILE The per-process limit on the number of open file descriptors has been reached.

       ENFILE The system-wide limit on the total number of open files has been reached.

       ENOENT Directory does not exist, or name is an empty string.

       ENOMEM Insufficient memory to complete the operation.

       ENOTDIR
              name is not a directory.
```



#### 14.2.1.2 读取目录的函数readdir

```sh
NAME
       readdir - read a directory

SYNOPSIS
       #include <dirent.h>

       struct dirent *readdir(DIR *dirp);

DESCRIPTION
       The readdir() function returns a pointer to a dirent structure representing the next directory entry in the directory stream pointed to
       by dirp.  It returns NULL on reaching the end of the directory stream or if an error occurred.

       In the glibc implementation, the dirent structure is defined as follows:

           struct dirent {
               ino_t          d_ino;       /* Inode number */
               off_t          d_off;       /* Not an offset; see below */
               unsigned short d_reclen;    /* Length of this record */
               unsigned char  d_type;      /* Type of file; not supported
                                              by all filesystem types */
               char           d_name[256]; /* Null-terminated filename */ #以’\0‘结尾的文件名
           };

       The only fields in the dirent structure that are mandated by POSIX.1 are d_name and d_ino.  The other fields  are  unstandardized,  and
       not present on all systems; see NOTES below for some further details.

       The fields of the dirent structure are as follows:

       d_ino  This is the inode number of the file.

       d_off  The  value  returned  in  d_off  is the same as would be returned by calling telldir(3) at the current position in the directory
              stream.  Be aware that despite its type and name, the d_off field is seldom any kind of directory offset on modern  filesystems.
              Applications should treat this field as an opaque value, making no assumptions about its contents; see also telldir(3).

       d_reclen
              This  is  the  size (in bytes) of the returned record.  This may not match the size of the structure definition shown above; see
              NOTES.

       d_type This field contains a value indicating the file type, making it possible to avoid the expense of  calling  lstat(2)  if  further
              actions depend on the type of the file.

              When  a  suitable  feature test macro is defined (_DEFAULT_SOURCE on glibc versions since 2.19, or _BSD_SOURCE on glibc versions
              2.19 and earlier), glibc defines the following macro constants for the value returned in d_type:

              DT_BLK      This is a block device.

              DT_CHR      This is a character device.

              DT_DIR      This is a directory.

              DT_FIFO     This is a named pipe (FIFO).

              DT_LNK      This is a symbolic link.

              DT_REG      This is a regular file.

              DT_SOCK     This is a UNIX domain socket.

              DT_UNKNOWN  The file type could not be determined.

              Currently, only some filesystems (among them: Btrfs, ext2, ext3, and ext4) have full support for  returning  the  file  type  in
              d_type.  All applications must properly handle a return of DT_UNKNOWN.

       d_name This field contains the null terminated filename.  See NOTES.

       The data returned by readdir() may be overwritten by subsequent calls to readdir() for the same directory stream.

RETURN VALUE
       On  success, readdir() returns a pointer to a dirent structure.  (This structure may be statically allocated; do not attempt to free(3) it.)

       If the end of the directory stream is reached, NULL is returned and errno is not changed.  If an error occurs,  NULL  is  returned  and errno  is set appropriately.  To distinguish end of stream and from an error, set errno to zero before calling readdir() and then check the value of errno if NULL is returned. #如果到达了目录流的末尾，返回NULL并且errno不会改变。 如果发生了error，返回NULL并且相应地设置errno。为了区分流结束和错误，在调用readdir()之前将errno设置为0，如果返回NULL，检查errno的值。

ERRORS
       EBADF  Invalid directory stream descriptor dirp.

```



### 14.3.2 实现简单的ls

功能：实现简单的<span style="color:red">`ls`</span>

1. 可以有<span style="color:red">`0`</span>个到 <span style="color:red">`多个`</span>参数
2. 参数可以是文件，也可以是目录；
3. 如果没有参数，使用缺省的<span style="color:red">`.`</span>;
4. 输出每个目录下所有的文件名；
5. 如果参数是文件，则只输出文件名；

> 具体显示样式，可以参考<span style="color:red">`ls`</span>命令

```C
#include <stdio.h>
#include <unistd.h>
#include <sys/types.h>
#include <dirent.h>

void do_ls(const char *);
int dir_num = 0; //参数数量

//ls a.x b.y
int main(int argc, char **argv) {
    dir_num = argc;
    if (argc == 1) {
        do_ls(".");
    } else {
        for (int i = 1; i < argc; i++) {
            do_ls(argv[i]);
        }
    }
    return 0;
}

void do_ls(const char *name) {
    DIR *dir = NULL;
    struct dirent *direntp;
    if ((dir = opendir(name)) == NULL) {
        if (access(name, R_OK) == 0) {  //如果打不开，但是能访问，那就是文件
            printf("%s ", name);
        }
    } else {
        if (dir_num > 2) printf("%s:\n", name);
        while ((direntp = readdir(dir))) {
            printf("\033[31;34m%s\033[0m ", direntp->d_name);
        }
        printf("\n");
    }
    return ;
}
```

运行效果：

![image-20201018131356130](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201018131356130.png)

但是举例系统的ls功能，还需要排序(大小写的开头的排在一起）、分页（屏幕大小，几列几行）、着色(不同类型的文件颜色不同，权限和文件类型 env变量中的LS_COLORS变量)。

### 14.3.3 实现更复杂的ls 

1. 实现简单的<span style="color:red">`ls`</span>, 支持<span style="color:red">`-a`</span>和<span style="color:red">`-l`</span>选项，请使用<span style="color:red">`getopt`</span>来解析参数。

    **参数说明**

    1. 可以有<span style="color:red">`0`</span>个到 <span style="color:red">`多个`</span>参数
    2. 参数可以是文件，也可以是目录；
    3. 如果没有参数，使用缺省的<span style="color:red">`.`</span>
    4. 如果参数是文件，则只输出文件名；

    **执行说明**

    1. `ls`显示所有未隐藏的文件，排序，分类显示，着色
    2. `ls -a`将显示所有的文件，排序，分列显示，着色
    3. `ls -l`将显示不隐藏的文件，排序，按行显示文件的详细信息，着色
    4. `ls -al`将显示所有文件，排序，按行显示文件的详细信息，着色

    > 具体显示样式，可以参考<span style="color:red">`ls`</span>命令

所以在之前的程序的基础上，还需要如下4步：

1. 排序

    1. 快排

    ```C
    char *str[512]; //表示的是一个指针数组，数组中有512个元素，每个元素都是指针变量，数组大小为512 * 8 = 4096Byte，如果参数接收可以将参数写为char *str[]
    char (*str)[512]; //表示的是一个指针数组的指针，sizeof(str) = 8Byte
    char str[512][511]; //512个元素，每个元素大小为511个字符,参数接收方式char (*str)[511]
    ```

    vim实用：vim 替换文件中全部匹配的字符串并保存

    ```sh
    :%s/old/new/g #将文件中所有的字符串old替换为new
    ```

2. 分列显示 : 排好序后每一列名称最长的来确定一列应该占多大

    1. 获取窗口大小 （终端窗口大小, ioctl）

    ```C
    #include <stdio.h>
    #include <stdlib.h>
    #include <sys/ioctl.h>
    #include <sys/types.h>
    #include <unistd.h>
    #include <string.h>
    
    int main() {
        struct winsize size;
        memset(&size, 0, sizeof(size));
        while (1) {
            sleep(1);
            if (ioctl(STDOUT_FILENO, TIOCGWINSZ, &size) < 0) {
                perror("ioctl()");
                exit(1);
            }
            printf("col = %d\n", size.ws_col); //都是字节数
            printf("row = %d\n", size.ws_row);
        }
        return 0;
    }
    ```

3. 着色

4. 显示文件的详细信息

    1. 文件类型`man inode`, stat函数
    2. 用户`uid->username`: `getpwuid(uid)` （访问/etc/passwd文件）
    3. 组`uid->groupname`: `getgrgid(gid)`
    4. 时间：`ctime`, 默认是mtime

如果要查找结构体中的类型定义，使用ctags的功能。

```
ctrl + ]:进入定义
ctrl + o:返回上一级
```

思维流程图：

<img src="Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201022211504108.png" alt="image-20201022211504108"  />

show_files函数的输出下标 j 以及size_window函数中 y 的说明：

![image-20201022233652633](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201022233652633.png)

```c
#include <stdio.h>
#include <unistd.h>
#include <sys/types.h>
#include <dirent.h>
#include <stdlib.h>
#include <sys/types.h>
#include <sys/ioctl.h>
#include <string.h>
#include <math.h>
#include <sys/stat.h>
#include <time.h>
#include <pwd.h>
#include <grp.h>

//最多：1024个文件，文件长度为512字节
#define MAXFILE 1024
#define MAXNAME 512

int a_flag = 0;
int l_flag = 0;
int *wide;
int bg_c, fg_c;

void do_ls(const char *);
void do_stat(const char *);
void size_window(char filename[][MAXNAME], int num, int *row, int *col);
void show_file(char filename[][MAXNAME], int num, int row, int col);
void show_info(const char *filename, struct stat *st);

void update_color(mode_t mode) {
    bg_c = 40;
    fg_c = 37;
    if (mode & (S_IXUSR | S_IXGRP | S_IXOTH)) fg_c = 32; //可执行文件
    switch (mode & S_IFMT) {
        case S_IFDIR: fg_c = 34; break;
        case S_IFCHR: fg_c = 33; break;
        case S_IFLNK: fg_c = 36; break;
    }
}

int dir_num = 0; //参数数量
//ls a.x b.y
int main(int argc, char **argv) {
    int opt;
    while ((opt = getopt(argc, argv, "al")) != -1) { //getopt函数会自动调整选项和参数
        switch (opt) {
            case 'a':
                a_flag = 1;
                break;
            case 'l':
                l_flag = 1;
                break;
            default:
                fprintf(stderr, "Usage : %s [-al] file...\n", argv[0]);
                exit(1);
        }
    }
    argc -= (optind - 1);
    argv += (optind - 1);

    dir_num = argc;
    if (argc == 1) {
        do_ls(".");
    } else {
        for (int i = 1; i < argc; i++) {
            do_ls(argv[i]);
        }
    }
    return 0;
}

void do_ls(const char *name) {
    DIR *dir = NULL;
    struct dirent *direntp;
    char names[MAXFILE][MAXNAME] = {0};
    if ((dir = opendir(name)) == NULL) {
        if (access(name, R_OK) == 0) {  //如果打不开，但是能访问，那就是文件
            if (l_flag) {
                do_stat(name);
            } else {
                struct stat tmp_st;
                lstat(name, &tmp_st);
                update_color(tmp_st.st_mode);
                printf("\033[%d;%dm%s\033[0m ",bg_c, fg_c, name);
            }
        }
    } else {
        if (dir_num > 2) printf("%s:\n", name);
        int cnt = 0;
        while ((direntp = readdir(dir))) {
            //printf("%s ", direntp->d_name);
            if (a_flag == 0 && direntp->d_name[0] == '.') { //没有-a选项，且文件第一个字符为'.'（隐藏文件）
                continue;
            }
            strcpy(names[cnt++], direntp->d_name);
        }
        //TODO: 研究一下系统快排
        //qsort(name, cnt, MAXNAME, cmp_name); //系统快排函数
        if (l_flag == 0) {
            int row, col;
            size_window(names, cnt, &row, &col);
            printf("row = %d, col = %d\n", row, col); //终端显示的行列数row， col
            show_file(names, cnt, row, col); //数组作为参数传递会退化为指针，因为不知道到底多大，所以要传cnt
        } else {
            for (int i = 0; i < cnt; i++) {
                //TODO:  ./a.out -l /etc 会出现错误
                //a.out程序路径添加到系统PATH路径中的话，在任何地方都能执行a.out
                do_stat(names[i]);
            }
        }
        printf("\n");
    }
    return ;
}


void size_window(char filename[][MAXNAME], int num, int *row, int *col) { //分列显示
    struct winsize size;
    int len[num], max = 0, total = 0; //len为可变数组,max记录最长的字符串。total为所有字符串总长
    memset(len, 0, sizeof(int) * num);
    if (ioctl(STDOUT_FILENO, TIOCGWINSZ, &size) < 0) {
        perror("ioctl");
        exit(1);
    }
    // +1都是加的一个空格
    for (int i = 0; i < num; i++) { //保存每个文件的名称并找出最长的文件名称
        len[i] = strlen(filename[i]);
        if (max < len[i]) max = len[i];
        total += len[i] + 1;
    }
    if (max + 1 >= size.ws_col) { //文件名最长的已经大于宽(列)，只能放一列多行，行数为文件个数
        *row = num;
        *col = 1;
        return ;
    }

    if (total <= size.ws_col) { //所有文件名的总长小于宽(列)，则只用一行即可放置，列数为文件个数
        *row = 1;
        *col = num;
        return ;
    }

    int try_begin = 0; //尝试一共应该放几列
    for (int i = 0, len_temp = 0; i < num; i++) { //尝试可以放置的列数
        len_temp += (len[i] + 1); // +1为后面的空格
        if (len_temp >= size.ws_col) { //将i个文件名称长度加起来，如果大于终端宽度，则说明一行可以放置i个文件
            try_begin = i; //try_begin就为尝试到的能放置的列数
            break;
        }
    }

    for (int i = try_begin - 1; ; i--) { //i是列数
        wide = (int *)malloc(sizeof(int) * i); //另一个可变数组,保存每一列最长的字符串
        int try_sum = 0; //一行能放置的文件个数
        *row = (int)ceil(num / i);
        for (int x = 0; x < i; x++) { //对每一列循环
            for (int y = x * *row; y < (x + 1) * *row && y < num; y++) { //找出一列中长度最大的文件
                if (wide[x] < len[y]) wide[x] = len[y];
            }
            try_sum += (wide[x] + 1);
        }
        if (try_sum > size.ws_col) { //按照当前i列的方式排列，会超出终端宽度，于是进入下一次循环(i - 1)即减少一列的方式
            continue;
        } else {
            *col = i; //否则当前i列的方式可以成功排列当前的文件
            break;
        }
    }
}

void show_file(char filename[][MAXNAME], int cnt, int row, int col) { //分列输出
    if (row == 1) { //如果一行显示
        for (int i = 0; i < cnt; i++) {
            struct stat tmp_stat;
            lstat(filename[i], &tmp_stat);
            update_color(tmp_stat.st_mode);
            printf("\033[%d;%dm%s\033[0m  ",fg_c, bg_c, filename[i]);
        }
        printf("\n");
        return ;
    }
    if (col == 1) {
        for (int i = 0; i < cnt; i++) {
            struct stat tmp_stat;
            lstat(filename[i], &tmp_stat);
            update_color(tmp_stat.st_mode);
            printf("\033[%d;%dm%s\033[0m\n",fg_c, bg_c, filename[i]);
        }
        return ;
    }
    for (int i = 0; i < row; i++) {
        for (int j = i; j < i + (row * col) && j < cnt; j = j + row) {
            int tmp = j / row;
            struct stat tmp_stat;
            lstat(filename[j], &tmp_stat);
            update_color(tmp_stat.st_mode);
            printf("\033[%d;%dm%-*s\033[0m",bg_c, fg_c, wide[tmp] + 1, filename[j]);
        }
        printf("\n");
    }
}

void do_stat(const char *filename) {
    struct stat st;
    if (lstat(filename, &st) < 0) {
        perror("lstat");
        exit(1);
    }
    show_info(filename, &st); //结构体通常是使用指针传递，如果直接传结构体，会效率较低
}

void mode_to_str(char *modestr, mode_t mode) {
    if (S_ISREG(mode)) modestr[0] ='-';
    if (S_ISDIR(mode)) modestr[0] ='d';
    if (S_ISCHR(mode)) modestr[0] ='c';
    if (S_ISBLK(mode)) modestr[0] ='b';
    if (S_ISSOCK(mode)) modestr[0] ='s';
    if (S_ISFIFO(mode)) modestr[0] ='p';
    if (S_ISLNK(mode)) modestr[0] ='l';

    if (mode & S_IRUSR) modestr[1] = 'r';
    if (mode & S_IWUSR) modestr[1] = 'w';
    if (mode & S_IXUSR) modestr[1] = 'x';

    if (mode & S_IRGRP) modestr[1] = 'r';
    if (mode & S_IWGRP) modestr[2] = 'w';
    if (mode & S_IXGRP) modestr[3] = 'x';

    if (mode & S_IRUSR) modestr[4] = 'r';
    if (mode & S_IWUSR) modestr[5] = 'w';
    if (mode & S_IXUSR) modestr[6] = 'r';

    if (mode & S_IROTH) modestr[7] = 'r';
    if (mode & S_IWOTH) modestr[8] = 'w';
    if (mode & S_IXOTH) modestr[9] = 'x';
}

char *uid_to_name(uid_t uid) {
    struct passwd *pw_ptr;
    static char tmpname[20] = {0};
    if ((pw_ptr = getpwuid(uid)) == NULL) {
        sprintf(tmpname, "%d", uid);
        return tmpname; //局部变量返回没有意义，因为返回它的内存就被销毁了，因此加static修饰
    } else {
        return pw_ptr->pw_name;
    }
}
char *gid_to_name(gid_t gid) {
    struct group *gr_ptr;
    static char tmpname[20] = {0};
    if ((gr_ptr = getgrgid(gid)) == NULL) {
        sprintf(tmpname, "%d", gid);
        return tmpname; //局部变量返回没有意义，因为返回它的内存就被销毁了，因此加static修饰
    } else {
        return gr_ptr->gr_name;
    }
}

void show_info(const char *filename, struct stat *st) { //此处写了固定字宽，应该优化为将当前目录下所有信息保存下来，找到各个字段最长的那个，根据最长的长度来确定字宽
    char modestr[15] = "----------"; //权限字符串
    mode_to_str(modestr, st->st_mode); //将权限转换为字符串
    printf("%s ", modestr);
    printf("%5ld ", st->st_nlink);
    printf("%5s ", uid_to_name(st->st_uid));
    printf("%5s ", gid_to_name(st->st_gid));
    printf("%7ld ", st->st_size);
    printf("%.15s ", 4 + ctime(&st->st_mtime)); //不要周几的显示,因为ctime的结果为一个字符串的首地址，所以对首地址进行操作可以自己选择从哪个字符开始输出
    update_color(st->st_mode);
    printf("\033[%d;%dm%s\033[0m\n", bg_c, fg_c, filename);
}
```

还需要实现及修复的Bug：

1、排序（qsort快排）

2、指定路径的时候会出现错误：`./a.out -l /etc`

3、着色有时候会出现问题

4、学习：printf格式化字符串中的`-`和`.`的作用。

## 14.4 多进程编程

第一个涉及到的函数为`fork`。

> **NAME**
>        fork - create a child process
>
> **SYNOPSIS**
>        #include <sys/types.h>
>        #include <unistd.h>
>
> ​       pid_t fork(void);
>
> **DESCRIPTION**
>        ***fork***() creates a new  process  by  duplicating the calling process.  The new process is referred to as the child process.  The calling process is referred to as the parent process.
>
> ​       The child process and the parent process run in separate memory spaces.  At the time of fork() both memory spaces have  the  same  content.   Memory writes, file mappings (mmap(2)), and unmappings (munmap(2)) performed by one of the processes do not affect the other.
>
> -  **The child process is an exact duplicate of the parent process except for the following points:**
>
>        - The child has its own unique process ID, and this PID does not match the ID of any existing process group (setpgid(2)) or session.
>        - The child's parent process ID is the same as the parent's process ID.
>        - The child does not inherit its parent's memory locks (mlock(2), mlockall(2)).
>        - Process resource utilizations (getrusage(2)) and CPU time counters (times(2)) are reset to zero in the child.
>        - The child's set of pending signals is initially empty (sigpending(2)).
>        - The child does not inherit semaphore adjustments from its parent (semop(2)).
>        - The  child  does  not inherit process-associated record locks from its parent (fcntl(2)).  (On the other hand, it does inherit fcntl(2) open file description locks and flock(2) locks from its parent.)
>        - The child does not inherit timers from its parent (setitimer(2), alarm(2), timer_create(2)).
>        - The child does not inherit outstanding asynchronous I/O operations from its parent (aio_read(3), aio_write(3)), nor does it inherit any asynchronous I/O contexts from its parent (see io_setup(2)).
>
>    - **The  process  attributes  in the preceding list are all specified in POSIX.1.  The parent and child also differ with respect to the following Linux-specific process attributes:**
>
>            *  The child does not inherit directory change notifications (dnotify) from its parent (see the description of F_NOTIFY in fcntl(2)).
>            *  The prctl(2) PR_SET_PDEATHSIG setting is reset so that the child does not receive a signal when its parent terminates.
>            *  The default timer slack value is set to the parent's current timer slack value.  See the description of PR_SET_TIMERSLACK in prctl(2).
>            *  Memory mappings that have been marked with the madvise(2) MADV_DONTFORK flag are not inherited across a fork().
>            *  Memory in address ranges that have been marked with the madvise(2) MADV_WIPEONFORK flag is zeroed in the child after a fork().  (The MADV_WIPEON‐FORK setting remains in place for those address ranges in the child.)
>            *  The termination signal of the child is always SIGCHLD (see clone(2)).
>            
>                *  The  port  access  permission  bits  set by ioperm(2) are not inherited by the child; the child must turn on any bits that it requires using ioperm(2).
>
> -  **Note the following further points:**
>
>        - The child process is created with a single thread—the one that called fork().  The entire virtual address space of the parent  is  replicated  in the  child,  including  the  states  of mutexes, condition variables, and other pthreads objects; the use of pthread_atfork(3) may be helpful for dealing with problems that this can cause.
>
>     - After a fork() in a multithreaded program, the child can safely call only async-signal-safe functions (see signal-safety(7)) until such  time  as it calls execve(2).
>
>
>        *  The  child inherits copies of the parent's set of open file descriptors.  Each file descriptor in the child refers to the same open file description (see open(2)) as the corresponding file descriptor in the parent.  This means that the two file descriptors share open  file  status  flags,file offset, and signal-driven I/O attributes (see the description of F_SETOWN and F_SETSIG in fcntl(2)).
>        *  The  child  inherits copies of the parent's set of open message queue descriptors (see mq_overview(7)).  Each file descriptor in the child refers to the same open message queue description as the corresponding file descriptor in the parent.  This means that the two  file  descriptors  share the same flags (mq_flags).
>        *  The  child inherits copies of the parent's set of open directory streams (see opendir(3)).  POSIX.1 says that the corresponding directory streams in the parent and child may share the directory stream positioning; on Linux/glibc they do not.
>
> **RETURN VALUE**   (返回值)
>        On success, the PID of the child process is returned in the parent, and 0 is returned in the child.  
>        On failure, -1 is returned in the  parent,  no child process is created, and errno is set appropriately.
>
> **ERRORS**
>        ==EAGAIN== A system-imposed limit on the number of threads was encountered.  There are a number of limits that may trigger this error:
>
>    *  the  RLIMIT_NPROC  soft  resource  limit  (set via setrlimit(2)), which limits the number of processes and threads for a real user ID, was reached;
>    *  the kernel's system-wide limit on the number of processes and threads, /proc/sys/kernel/threads-max, was reached (see proc(5));
>    *  the maximum number of PIDs, /proc/sys/kernel/pid_max, was reached (see proc(5)); or
>    *  the PID limit (pids.max) imposed by the cgroup "process number" (PIDs) controller was reached.
>
> ​      ==EAGAIN== The caller is operating under the SCHED_DEADLINE scheduling policy and does not have the reset-on-fork flag set.  See sched(7).
>
> ​       ==ENOMEM fork()== failed to allocate the necessary kernel structures because memory is tight.
>
> ​       ==ENOMEM== An attempt was made to create a child process in a PID namespace whose "init" process has terminated.  See pid_namespaces(7).
>
> ​       ==ENOSYS fork()== is not supported on this platform (for example, hardware without a Memory-Management Unit).
>
> ​       ==ERESTARTNOINTR== (since Linux 2.6.17)
> ​              System call was interrupted by a signal and will be restarted.  (This can be seen only during a trace.)

### 14.4.1 创建进程 fork

#### 1、fork的使用

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>

int main() {
    pid_t pid;
    if ((pid = fork()) < 0) {
        perror("fork");
        exit(1);
    }
    if (pid == 0) { //子进程
        printf("I am child!\n");
    } else {
        printf("I am parent!\n");
    }

    return 0;
}
```

哪个语句先输出，是不确定的。根据进程调度，很大概率是父进程先执行。输出结果：

```sh
I am parent!
I am child!
```

如果想让子进程确切地先执行，可以使父进程先睡一会儿：

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>

int main() {
    pid_t pid;
    if ((pid = fork()) < 0) {
        perror("fork");
        exit(1);
    }
    if (pid == 0) { //子进程
        printf("I am child!\n");
    } else {
        sleep(1);
        printf("I am parent!\n");
    }

    return 0;
}
```

运行结果：

```sh
I am child!
I am parent!
```

但是一般不会通过这种方式来使得某个进程先执行。sleep的时间精度是1s，还有一个更小时间精度的函数usleep，精度为微秒。

```c
usleep(100); //睡眠100微秒
```

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>

int main() {
    pid_t pid;
    printf("I'm Father!");
    if ((pid = fork()) < 0) {
        perror("fork");
        exit(1);
    }
    if (pid == 0) { //子进程
        printf("I am child!\n");
    } else {
        sleep(1);
        printf("I am parent!\n");
    }

    return 0;
}
```

输出结果为：

```sh
I'm Father!I am child!
I'm Father!I am parent!
```

出现这个的原因是`行缓冲机制`。`stdio.h`中定义的I/O操作都是缓冲I/O，即printf不会一个一个字符地输出，而是以行为基本单位输出。上面的代码第7行在输出缓冲区等着，还没来得及输出，第8行复制了两份，父子进程都有这个缓冲区了，因此父子进程输出的时候都会将这个标准输出给输出出来。

#### 2、创建100个进程

> 使用fork，创建100个子进程

每个子进程输出 `I'm %dth Child!`

错误示例：

```C
#include <stdio.h>
#include <unistd.h>

int main() {
    for (int i = 0; i <= 100; i++) {
        pid_t pid;
        if ((pid = fork()) < 0) {
            perror("fork");
            exit(1);
        }
    }
    return 0;
}
```

该程序运行会提示：`fork：Resource temporarily unavailable`，该代码会fork指数级个子进程。

```C
#include <stdio.h>
#include <unistd.h>

int main() {
    pid_t pid;
    int x;
    for (int i = 1; i <= 100; i++) {
        x = i;
        if ((pid = fork()) < 0) {
            perror("fork");
            exit(1);
        }
        if (pid == 0) { //只有父进程负责生孩子，子进程不需要
            break;
        }
    }
    if (pid == 0) {
        printf("I'm %dth Child!\n",x);
        sleep(100); //使子进程再活100s
    }
    return 0;
}
```

会成功生成100个子进程。该代码中，父进程生完子进程后就会死亡。

![image-20201019131527596](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019131527596.png)

可以看到，子进程的父进程都是1，是因为在子进程创建完毕后，父进程就死了，子进程变成了孤儿，被1号进程收养。进程总的个数为100：

![image-20201019131649000](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019131649000.png)

如果让父进程稍微活长一点：

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>

//生一个孩子，孩子就出去做自己的事
//父进程还在for循环里，直到将for循环执行完毕
int main() {
    pid_t pid;
    int x;
    for (int i = 1; i <= 100; i++) {
        x = i;
        if ((pid = fork()) < 0) {
            perror("fork");
            exit(1);
        }
        if (pid == 0) { //只有父进程负责生孩子，子进程不需要
            break;
        }
    }
    if (pid == 0) {
        printf("I'm %dth Child!\n",x);
        sleep(100); //使子进程再活100s
    } else {
        sleep(200); //父进程活的比子进程稍微长一点时间
    }
    return 0;
}
```

输出的时候会发现父进程占据着标准输出，显示为如下：

![image-20201019131933349](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019131933349.png)

使用ctrl+z让该程序在后台运行，然后查看进程信息：

![image-20201019132044866](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019132044866.png)

可以看到父进程为28309，父进程等待子进程活过100s。进程的个数一共为101个：

![image-20201019132111706](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019132111706.png)

**如何让这些子进程变为僵尸进程呢？** 

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>

//生一个孩子，孩子就出去做自己的事
//父进程还在for循环里，直到将for循环执行完毕
int main() {
    pid_t pid;
    int x;
    for (int i = 1; i <= 100; i++) {
        x = i;
        if ((pid = fork()) < 0) {
            perror("fork");
            exit(1);
        }
        if (pid == 0) { //只有父进程负责生孩子，子进程不需要
            break;
        }
    }
    if (pid == 0) {
        printf("I'm %dth Child!\n",x);
        sleep(1); //使子进程再活1s
    } else {
        sleep(200); //父进程活的比子进程稍微长一点时间
    }
    return 0;
}
```

让这个程序在后台运行，就会出现100个僵尸进程（僵尸进程产生的原因就是子进程死了，父进程还不做处理）。

#### 3、fork后的子进程从哪里开始执行

fork将父进程的代码复制一份，子进程从fork后的代码开始执行，并非从头到尾执行。



### 14.4.2 进程等待 wait

父进程活着，子进程死了，为了防止其成为僵尸进程，就需要给它收尸。这就涉及到了函数wait

> **NAME**
>        wait, waitpid, waitid - wait for process to change state
>
> **SYNOPSIS**
>        #include <sys/types.h>
>        #include <sys/wait.h>
>
> ```c
>    pid_t wait(int *wstatus);
> 
>    pid_t waitpid(pid_t pid, int *wstatus, int options);
> 
>    int waitid(idtype_t idtype, id_t id, siginfo_t *infop, int options);
>                    /* This is the glibc and POSIX interface; see
>                       NOTES for information on the raw system call. */
> ```
>
>    Feature Test Macro Requirements for glibc (see feature_test_macros(7)):
>
> ```c
>    waitid():
>        Since glibc 2.26: _XOPEN_SOURCE >= 500 ||
>            _POSIX_C_SOURCE >= 200809L
>        Glibc 2.25 and earlier:
>            _XOPEN_SOURCE
>                || /* Since glibc 2.12: */ _POSIX_C_SOURCE >= 200809L
>                || /* Glibc versions <= 2.19: */ _BSD_SOURCE
> ```
>
> **DESCRIPTION**
>        All  of  these system calls are used to wait for state changes in a child of the calling process, and obtain information about the child whose state has changed.  A state change is considered to be: the child terminated; the child was stopped by a signal; or the child was resumed by a signal.  **<span style="color:red">In the  case of a terminated child, performing a wait allows the system to release the resources associated with the child; if a wait is not performed,then the terminated child remains in a "zombie" state</span>**(执行wait操作运行系统释放相关子进程的资源，如果没有执行wait，那么相关子进程会进入”僵尸“状态) (see NOTES below).
>
>   > ==If a child has already changed state, then these calls return immediately.  Otherwise, they block until either a child changes  state  or  a  signal handler  interrupts the call (assuming that system calls are not automatically restarted using the SA_RESTART flag of sigaction(2)).  In the remainder of this page, a child whose state has changed and which has not yet been waited upon by one of these system calls is termed waitable.== (僵尸状态说明)



```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <sys/wait.h>

int main() {
    pid_t pid;
    int x;
    for (int i = 1; i <= 100; i++) {
        x = i;
        if ((pid = fork()) < 0) {
            perror("fork");
            exit(1);
        }
        if (pid == 0) { //只有父进程负责生孩子，子进程不需要
            break;
        }
    }
    if (pid == 0) {
        printf("I'm %dth Child!\n",x);
        sleep(1); //使子进程再活100s
    } else {
        for (int i = 1; i <= 100; i++) {
            wait(NULL); //父进程等待子进程死掉，允许系统释放资源
        }
    }

    return 0;
}
```

运行结果：执行`a.out`程序，没有进程占用着终端：

![image-20201019164728473](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019164728473.png)

可以看到没有僵尸进程：

![image-20201019164645283](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019164645283.png)

**wait只等待其中任意一个子进程死亡**。

**如果wait的次数大于fork的次数呢？**

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <sys/wait.h>

int main() {
    pid_t pid;
    int x;
    for (int i = 1; i <= 100; i++) {
        x = i;
        if ((pid = fork()) < 0) {
            perror("fork");
            exit(1);
        }
        if (pid == 0) { //只有父进程负责生孩子，子进程不需要
            break;
        }
    }
    if (pid == 0) {
        printf("I'm %dth Child!\n",x);
        sleep(1); //使子进程再活100s
    } else {
        for (int i = 1; i <= 100; i++) {
            wait(NULL); //等待子进程死掉,返回的是死亡的子进程的pid
        }
        int tmp = wait(NULL);
        printf("%d\n", tmp); //结果为-1，已经没有需要收尸的子进程了
    }

    return 0;
}
```

**查看等待状态返回码**

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <sys/wait.h>

int main() {
    pid_t pid;
    int x;
    for (int i = 1; i <= 100; i++) {
        x = i;
        if ((pid = fork()) < 0) {
            perror("fork");
            exit(1);
        }
        if (pid == 0) { //只有父进程负责生孩子，子进程不需要
            break;
        }
    }
    if (pid == 0) {
        printf("I'm %dth Child!\n",x);
        sleep(1); //使子进程再活100s
    } else {
        for (int i = 1; i <= 100; i++) {
            int wstatus;
            pid_t rpid = wait(&wstatus);
            printf("Child %d returns with code %d\n", rpid, wstatus);
        }

        pid_t tmp = wait(NULL);
        printf("%d\n", tmp); //-1
    }

    return 0;
}
```

运行结果：（部分截图）

![image-20201019165542650](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019165542650.png)

### 14.4.3 进程变身 exec

> **NAME**
>        execl, execlp, execle, execv, execvp, execvpe - execute a file
>
> **SYNOPSIS**
>
> ```C
> #include <unistd.h>
> 
> extern char **environ;
> 
> int execl(const char *path, const char *arg, .../* (char  *) NULL */); //l:list)
> int execlp(const char *file, const char *arg, .../* (char  *) NULL */); //(p:path)
> int execle(const char *path, const char *arg, .../*, (char *) NULL, char * const envp[] */); //(e:environment)
> int execv(const char *path, char *const argv[]); //（v：vector）
> int execvp(const char *file, char *const argv[]);
> int execvpe(const char *file, char *const argv[],char *const envp[]);
> ```
>
> 这些函数间的第一个区别：path表示取路径名作为参数，file表示取文件名作为参数。
>
> 当指定file作为参数时：
>
> - 如果file中包含/，则就将其视为路径名；
> - 否则就按PATH环境变量，在它所指定的各目录中搜寻可执行文件   
>
> 第二个区别：与参数表的传递有关（l表示列表list，v表示矢量vector）。函数execl、execlp、execle要求将新程序的每个命令行参数都说明为一个单独的参数。这种参数表以空指针结尾。另外的execv、execvp、execvpe，则应先构造一个指向各参数的指针数组，然后将该数组地址作为这4个函数的参数。对execl、execlp、execle三个函数表示命令行参数的一般方法是：
>
> ```C
> char *arg0, char *arg1, ..., char *argn, (char *)0
> ```
>
> 这种语法显式地说明了最后一个命令行参数之后跟了一个空指针。如果用常量0来表示一个空指针，则必须将它强制转换为一个指针；否则，它将被解释为整型参数。如果一个整型数的长度与char *的长度不同，那么exec函数的实际参数将出错。
>
> **exec函数的参数记忆帮助法**：字母**p**表示该函数取**filename**作为参数，并且用PATH环境变量寻找可执行文件。字母**l**表示该函数取一个参数表，它与字母v互斥。**v**表示该函数取一个 argv[]矢量。字母**e**表示该函数取envp[]数组，而不使用当前环境。

> Feature Test Macro Requirements for glibc (see feature_test_macros(7)):
>
> ```
> execvpe(): _GNU_SOURCE
> ```
>
> **DESCRIPTION**
>        ==The  exec() family of functions replaces the current process image with a new process image==.  The functions described in this manual page are front-ends for execve(2).  (See the manual page for execve(2) for further details about the replacement of the current process image.)
>
>    The initial argument for these functions is the name of a file that is to be executed. （第一个参数都是要执行的文件）
>
>    The const char *arg and subsequent ellipses in the execl(), execlp(), and execle() functions can be thought of as arg0, arg1, ...,  argn.   Together they  describe  a  list  of one or more pointers to null-terminated strings that represent the argument list available to the executed program.  The first argument, by convention, should point to the filename associated with the file being executed.  The list of arguments must be terminated by a null pointer, and, since these are variadic functions, this pointer must be cast (char *) NULL.
> 	The execv(), execvp(), and execvpe() functions provide an array of pointers to null-terminated strings that represent the argument list available to the new program.  The first argument, by convention, should point to the filename associated with the file being executed.  The array of pointers must be terminated by a null pointer.
>
> ​	The  execle()  and execvpe() functions allow the caller to specify the environment of the executed program via the argument envp.  The envp argument is an array of pointers to null-terminated strings and must be terminated by a null pointer.  The other functions take the environment for  the  new process image from the external variable environ in the calling process.
>
> **RETURN VALUE**
>        The exec() functions return only if an error has occurred.  The return value is -1, and errno is set to indicate the error.

exec使用示例：

```C
#include <stdio.h>
#include <unistd.h>
#include <sys/wait.h>
#include <stdlib.h>
int main() {
    pid_t pid;
    if ((pid = fork()) < 0) {
        perror("fork");
        exit(1);
    }
    if (pid == 0) {
        printf("I am Child\nI am doing a great job now!\n");
        execlp("cat", "cat", "3.exec.c", NULL);
        printf("I am dead!\n");
    } else {
        printf("I am father!\n");
        wait(NULL);
    }
}
```

执行结果:

![image-20201019171836749](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019171836749.png)

之所以子进程没有输出`I am dead！`，是因为在exec函数中有如下描述：

> The  exec() family of functions replaces the current process image with a new process image. （用新的进程镜像替换当前的进程镜像，即将程序进行了替换）

这个程序中就是用`cat`替换了当前代码段，执行execlp这个函数的一刻，子进程就已经没有上下所有的代码了，而只有cat这个程序的代码。所以就不会再输出`I am dead!`了。

#### 14.3.3.1 exec的使用1：模拟git commit

> 该题目模拟 `git commit`的使用，如果没有给定`-m`参数，则打开一个`vim`编辑器，编辑好之后会继续执行。

现在要完成如下的程序：

文件名：`my_exec.c`->`my_exec`

1. 如果执行该程序时没有带`-m`选项，则打开一个`vim`编辑器，往一个文件`tmp.txt`中写东西

    1. 保存`vim`并退出后，调用`cat`打印出输入到`vim`文件中的内容

    ```shell
    ./my_exec
    ```

2. 如果带了`-m`选项，则直接输出`-m`后面所接的字符串：

    ```shell
    ./my_exec -m "hello"
    ```

```C
//my_exec.c
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <string.h>
#include <sys/wait.h>

int main(int argc, char **argv) {
    int opt;
    int m_flag = 0;
    char msg[512] = {0};
    while ((opt = getopt(argc, argv, "m:")) != -1) {
        switch (opt) {
            case 'm':
                printf("have m!\n");
                m_flag = 1;
                strcpy(msg, optarg);
                break;
            default:
                fprintf(stderr, "Usage : %s -m msg\n", argv[0]);
                exit(1);

        }
    }
    if (m_flag == 1) {
        printf("msg = %s\n", msg);
        return 0;
    }

    pid_t pid;
    if ((pid = fork()) < 0) {
        perror("fork");
        exit(1);
    }

    if (pid == 0) {
        // vim
        printf("We will open a Vim!\n");
        sleep(1);
        execl("/usr/bin/vim", "vim", "tmp.txt", NULL); //执行vim程序，第一个参数为vim程序所在的路径
    } else { //父进程
        wait(NULL); //等待子进程结束
        printf("Vim is out!\n");
        sleep(1);
        printf("Cat will be done!\n");
        sleep(1);
        execlp("cat", "cat", "tmp.txt", NULL); //执行cat程序
    }
    return 0;
}
```

然后编译执行：

![image-20201019213005408](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019213005408.png)

在vim中输入的正是“This is a msg from Maureen!"。

但是该程序有个问题，程序执行结束后有个tmp.txt，现在想在程序结束后直接删除掉tmp.txt：

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <string.h>
#include <sys/wait.h>

int main(int argc, char **argv) {
    int opt;
    int m_flag = 0;
    char msg[512] = {0};
    while ((opt = getopt(argc, argv, "m:")) != -1) {
        switch (opt) {
            case 'm':
                printf("have m!\n");
                m_flag = 1;
                strcpy(msg, optarg);
                break;
            default:
                fprintf(stderr, "Usage : %s -m msg\n", argv[0]);
                exit(1);

        }
    }
    if (m_flag == 1) {
        printf("msg = %s\n", msg);
        return 0;
    }

    pid_t pid;
    if ((pid = fork()) < 0) {
        perror("fork");
        exit(1);
    }

    if (pid == 0) {
        // vim
        printf("We will open a Vim!\n");
        sleep(1);
        execl("/usr/bin/vim", "vim", "tmp.txt", NULL);
    } else {
        pid_t pid1;
        wait(NULL); //等待子进程结束，也就是vim操作结束
        printf("Vim is out!\n");
        if ((pid1 = fork()) < 0) { //上一个子进程结束后立马再创建一个子进程
            perror("fork");
            exit(1);
        }
        if (pid1 == 0) { //让新的孩子去执行cat
            sleep(1);
            printf("Cat will be done!\n");
            sleep(1);
            execlp("cat", "cat", "tmp.txt", NULL);
        } else { //父进程执行删除tmp.txt的操作
            wait(NULL);
            printf("Cat is Over!\n Delete tmp.txt in 2s!\n");
            sleep(1);
            execlp("rm", "rm", "./tmp.txt", NULL);//execlp第一个参数直接就是可执行程序的名称
        }
    }
    return 0;
}
```

编译并允许：

![image-20201019214154211](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019214154211.png)

#### 14.3.3.2 exec的使用2：实现自动编译执行

1. 实现`my_run.c`，编译后`my_run`
2. 直接使用`my_run a.c`
3. 使用vim编辑完源码后，自动编译，并按照文件名生成可执行程序（比如prime.c，生成的可执行文件为prime）
4. 如果编译成功，则直接执行编译后的程序
5. 编译后的程序需要参数时，可直接通过此程序`my_run`的参数传入
6. 编译后的程序不需要参数，忽略此程序`my_run`中多余的参数

> ./my_run a.c maureen 18
> 输出：maureen is 18 years old！

注意：需要判断上一个操作的执行状态，如编译是否成功。

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <string.h>
#include <sys/wait.h>

int main(int argc, char **argv) {
    char filename[512] = {0};
    char f_type[512] = {0};
    char b_name[512] = {0};
    char g_cmd[512] = {0};
    if (argc < 2) { //没有额外参数
        fprintf(stderr, "Usage : %s filename.c arg...\n", argv[0]);
        exit(1);
    }

    strcpy(filename, argv[1]);
    char *sub;
	//C库函数 char *strrchr(const char *str, int c) 
    // 参数 str 所指向的字符串中搜索最后一次出现字符 c（一个无符号字符）的位置
    if ((sub = strrchr(filename, '.')) == NULL) {
        fprintf(stderr, "Filename is not supported!\n");
        exit(2);
    }

    strncpy(b_name, filename, sub - filename); //b_name该文件的名称不包含后缀名，若文件名test.c，就是test
    strcpy(f_type, sub);

    if (!strcmp(f_type, ".c")) { //如果是.c文件
        strcpy(g_cmd, "gcc");
    } else if (!strcmp(f_type, ".cpp")) { //如果是.cpp文件
        strcpy(g_cmd, "g++");
    } else {
        fprintf(stderr, "File type not supported!\n");
        exit(2);
    }

    pid_t pid;
    if ((pid = fork()) < 0) {
        perror("fork");
        exit(1);
    }

    if (pid == 0) {
        execlp("vim", "vim", filename, NULL);
    }
    wait(NULL);//等待vim退出
    if ((pid = fork()) < 0) {
        perror("fork");
        exit(1);
    }
    if (pid == 0) {
        execlp(g_cmd, g_cmd, filename, "-o", b_name, NULL);
    }
    int wstatus;
    wait(&wstatus);
    if (wstatus == 0) { //上条命令成功执行，即编译OK
        printf("Compile Ok\n");
        char tmp_name[512] = {0};
        sprintf(tmp_name, "./%s", b_name); //tmp_name为./test
       //printf("argv[0] = %s\n", *(argv + 1)); //得到的是test.c
        execv(tmp_name, argv + 1); //argv + 1 得到的是.c或者.cpp，是编译后将执行的程序的源文件
    } else {
        printf("Compile Failed!\n");
        exit(3);
    }

    return 0;
}
```

编译并运行：

![image-20201019223323277](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201019223323277.png)

```C
// test.c
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <string.h>

int main(int argc, char **argv) {
    int age;
    char name[20] = {0};

    if (argc != 3) { // ./test maureen 18
        fprintf(stderr, "Usage : %s name age!\n", argv[0]);
        exit(1);
    }
    strcpy(name, argv[1]);
    age = atoi(argv[2]); //ascii to integer，把字符串转换成整数
    printf("test.c:argv[0]=%s\n", argv[0]);
    printf("%s is %d years old!\n", name, age);

    return 0;
}
```

### 14.4.4 复习

#### 14.4.4.1 进程

1、进程是操作系统中**资源**分配与调度的最小单位；

2、进程是程序在内存中的镜像；

3、进程不是凭空产生的，系统中所有的进程都是由`systemd`进程克隆而来；

4、进程通过fork()函数赋值，而后通过exec()函数来进行”变身“，去完成各种各样的任务。

#### 14.4.4.2 进程的创建

- 在系统中，所有的进程都是由1号进程克隆而来，在我们进行系统编程的时候，可以使用`fork`函数来创建一个子进程，被克隆的进程叫做父进程。
- 父子进程在创建后，基本相同，除了以下几点：
  1. 子进程的`pid`是新分配的，与父进程不同
  2. 子进程的`ppid`会设置为父进程的`pid`
  3. 子进程中的资源统计信息会清零 (如父进程生存时长）
  4. 所有挂起的信号都会被清除，不会被子进程继承
  5. 所有文件锁也不会被子进程继承
```C
//fork函数：
#include <stdio.h>
#include <unistd.h>

int main() {
    pid_t pid;
    if ((pid = fork()) < 0) {
        perror("fork");
    }
    if (pid == 0) {
        printf("Child Process!\n");
    } else {
        printf("Parent Process!\n");
    }
    return 0;
}
```

#### 14.4.4.3 exec函数族说明

- 都是以`exec`开始，形式为`exec[lv][pe]`
    - 其中`l`和`v`分别表示用列表还是数组（向量）的方式提供参数
    - `p`表示会在用户的**`path`**路径下查找可执行文件
    - `e`表示会为新进程提供新的环境变量

#### 14.4.4.4 exec函数到底做了什么

1. 改变了地址空间和进程映像；
2. 挂起的所有信号都会丢失；
3. 后续捕捉到的所有信号都会还原为默认处理方式；
4. 丢弃所有内存锁；
5. 大多数线程属性会还原为默认值；
6. 重置大多数进程相关的统计信息；
7. 清空和进程内存地址空间相关的所有数据，包括所有映射的文件；
8. 清空所有只存在于用户空间的数据。

#### 14.4.4.5 进程的退出

```C
#include <stdlib.h>
void exit(int status);
```

status可以使用两个宏定义：`EXIT_SUCCESS`和`EXIT_FAILURE`。

在进程调用`exit`之后，C库会按顺序完成以下事件：

1. 调用任何由`atexit()`或`on_exit()`注册的函数；
2. 清空所有已打开的标准I/0流；
3. 删除由`tmpfile()`函数创建的所有临时文件；

完成上面的操作后，`exit()`会调用`_exit()`，内核接管下面的事：

1. 清理进程所创建的、不再使用的所有资源；
2. 销毁进程；
3. 告知父进程其子进程已被终止。

#### 14.4.4.5 wait() & waitpid()

- 子进程活着，父进程结束，则子进程变为**孤儿进程**
- 子进程死了，但父进程不为其”收尸“(释放资源)， 则子进程变为**僵尸进程**
- 孤儿进程可以被1号进程收养，对系统无害
- 僵尸进程已经不工作，但是依然占有资源，对系统有害，需避免

```c
#include <sys/types.h>
#include <sys/wait.h>
pid_t wait(int *status);
pid_t waitpid(pid_t pid, int *status, int options);
```

- wait和waitpid最终都会将子进程的退出状态放在status地址中
- waitpid中的第一个参数pid，可以有以下几个值：
    1. `pid < -1`: 等待一个进程组ID为pid绝对值的任何子进程退出，如果pid = -500，则等待进程组ID为500的任何子进程退出；
    2. `pid = -1`: 等待任何一个子进程退出，行为和`wait()`一致；
    3. `pid = 0`: 等待同一个进程组中的任何子进程退出；
    4. `pid > 0`: 等待进程pid为pid的子进程退出。
- option参数一般默认为0

## 14.5 多线程编程

### 14.5.1 线程

- 线程是操作系统调度器可调度的最小执行单元；
- 现代操作系统实现了两种对用户空间的基础虚拟抽象：虚拟内存和虚拟处理器；
- 进程感觉自己独占了内存，而线程感觉自己独占了处理器；
- 一个进程至少包含一个线程，一个进程的多个线程共享内存空间；
- 每个线程都独立调度，调度和切换的代价低于进程。

###  14.5.2 多线程的好处

1. 编程模块抽象化
2. 增加程序的并发性
3. 提高响应能力
4. IO阻塞可行
5. 上下文切换代价小
6. 内存保存，线程之间共享内存，切换无需置换内存

### 14.5.3 多线程坏处

1. 调试麻烦
2. 容易出现资源竞争

### 14.5.4 线程模式

- 每个连接对应一个线程 （每个游客进动物园就有一个猴子跟着，知道游客离开动物园）
    - 一个线程对应着一个连接或者请求，直到处理结束，这样线程才可以处理另一个新的请求了；
    - 在此模式下，将线程换成进程，就是老版的Unix服务器了，Apache的标准fork模式就是这种模式。
- 事件驱动的线程模式 （游客进入动物园，只有走到猴园的时候才会有只猴子跟着，离开猴园，猴子就等待下一个进入猴园的游客）
    - 将上个模式(每个连接对应一个线程) 中的负荷（等待）剥离出来，搭配异步IO或者IO复用来管理服务器中的数据流。
    - 在此模式下，将处理请求转换为一系列的异步IO和与其关联的回调函数；
    - 这些回调函数可通过IO多路复用的方式来等待，完成该操作的线程成为event_loop。

### 14.5.5 线程的竞争

- 同一个进程的线程共享内存空间，独立调度，并发执行时“重叠执行”，以不可预期的顺序执行，如果多个线程访问同一个资源，就产生了竞争，程序由于不确定哪个线程先执行而带来的行为不一致；
- 竞争的条件：两个或更多的线程对共享资源非同步访问；
- 共享资源可以是系统硬件、内核资源以及内存中的数据(data race)；
- 竞争发生的窗口，也就是需要同步的代码区称为**临界区**。

### 14.5.6 线程的同步

- 解决线程竞争的办法主要是线程同步，也就是让原先不确定的访问顺序，变得确定；
- 也就是要在临界区这个窗口内，要保证执行同步访问操作，确保对临界区的访问是互斥的；
- 最常见的实现就是在临界区前加**互斥锁**，在临界区后释放互斥锁，这样当一个线程占有锁的时候，其他线程就会被阻塞，直到被释放才可以获得锁，继续执行。 

### 14.5.7 多线程编程接口

#### 14.5.7.1 创建线程 pthread_create

```C
#include <pthread.h>
int pthread_create(pthread_t *thread, const pthread_attr_t *attr, 
                   void *(*start_routine)(void *), void *arg);
//Compile and link with -pthread.
```

- 参数thread：如果线程创建成功，将会把线程的ID保存到thread指向的空间；

- 参数attr：用于改变新创建线程的默认线程属性，一般默认NULL就可以；

- 参数start_routine：线程执行函数，形式应类似为-`void * start_thread(void *arg)`:
    - 参数为void指针
    - 返回值也是void指针

- 参数arg：arg为传递给第三个参数，也就是线程执行函数的参数，需要注意的是，**如果要传递多个参数，应该用结构体封装**。

#### 14.5.7.2 线程ID

- 线程ID和进程ID相似，但有一个本质的区别：==进程ID时由内核分配的，而线程ID是由**线程库**分配的==;
- 获取自己的线程ID：`pthread_t pthread_self(void);`
- 判断两个线程是否相同：`int pthread_equal(pthread_t t1, pthread_t t2);`
- 因为POSIX不要求pthread_t是一个算数类型，所以不能保证可以使用"=="判断线程ID是否相同。

#### 14.5.7.3 线程终止

- 线程会在下面的情况下退出，这和进程近似：
    1. 线程在启动时返回，该线程就结束
    2. 如果线程调用了`pthread_exit()`，线程就会终止
    3. 如果线程被另一个线程通过`pthread_cancel()`函数取消，也会终止
- 在以下场景中，所有线程都会被杀死，进程被杀死：
    1. 进程从主函数中返回
    2. 进程通过`exit()`函数终结

**线程的自杀**

```C
#include <pthread.h>
void pthread_exit(void *retval);

/*Goodbye, cruel world!*/
pthread_exit(NULL);
```

**线程的他杀**

```C
#include <pthread.h>
int pthread_cancel(pthread_t thread);

/*Could we climb mountains together?*/
pthread_cancel(you);
```

#### 14.5.7.4 线程加入(join)和分离(detach)

- 由于线程创建和销毁很容易，必须对线程进行同步的机制，避免被其他线程终止，对应的线程即`wait()`，也就是`join`线程；

- 线程join：支持一个线程阻塞，等待另一个线程终止

    ```C
    #include <pthread.h>
    int pthread_join(pthread_t pthread, void **retval);
    ```

- 线程detach：默认情况下，线程都是可join的，detach可以让其不可join

    ```C
    #include <pthread.h>
    int pthread_detach(pthread_t thread);
    ```

#### 14.5.7.5 线程互斥mutex

```C
#include <pthread.h>
pthread_mutex_t mutex = PTHREAD_MUTEX_INITIALIZER;
int pthread_mutex_lock(pthread_mutex_t *mutex);
int pthread_mutex_unlock(pthread_mutex_t *mutex); 
```

### 14.5.8 多线程示例

#### 线程接口的使用

1、创建一个线程输出"Maureen is 18 years old!"

```C
//1.pthread.c
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>

void *print() {
    printf("Maureen is 18 years old!\n");
}

int main() {
    pthread_t tid;
    pthread_create(&tid, NULL, print, NULL);
    return 0;
}
```

使用`gcc 1.pthread.c`编译出现如下错误：

```sh
4.pthread % gcc 1.pthread.c   #编译命令                                                           
/tmp/ccNNCJHp.o: In function `main':
1.pthread.c:(.text+0x43): undefined reference to `pthread_create'
collect2: error: ld returned 1 exit status
```

没有找到pthread_create的定义，这是因为没有链接线程库，使用如下方式编译即可：

```sh
gcc 1.pthread.c -lpthread
```

然后执行`./a.out`会发现没有结果输出。原因是主函数return之后，所有的线程都会终止，刚刚新创建的线程也会结束。

```C
//1.pthread.c
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>

void *print() {
    printf("Maureen is 18 years old!\n");
}

int main() {
    pthread_t tid;
    pthread_create(&tid, NULL, print, NULL);
    pthread_join(tid, NULL); //主函数会等待子线程结束再退出
    return 0;
}
```

这种方式就能成功输出`Maureen is 18 years old!`。

2、传一个参数给线程处理函数

```c
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>
#include <string.h>

void *print(void *arg) {
    printf("Maureen is %d years old!\n", *(int *)arg);
}

int main() {
    pthread_t tid;
    char name[20] = {0};
    int age = 18;
    strcpy(name, "Maureen");
    pthread_create(&tid, NULL, print, (void *)&age); //传入参数age
    pthread_join(tid, NULL); //主线程等待子线程结束后再退出
    return 0;
}
```

编译执行是ok的。

3、传多个参数给线程处理函数

```C
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>
#include <string.h>

struct MyArg {
    char name[20];
    int age;
};

void *print(void *arg) {
    struct MyArg *myarg = (struct MyArg *)arg;
    printf("%s is %d years old!\n", myarg->name, myarg->age);
}

int main() {
    pthread_t tid;
    struct MyArg myarg;
    myarg.age = 18;
    strcpy(myarg.name, "Maureen");
    pthread_create(&tid, NULL, print, (void *)&myarg);

    pthread_join(tid, NULL); //主线程等待子线程结束后再退出
    return 0;
}
```

编译运行也ok。

4、上面的方案存在一个问题

```C
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>
#include <string.h>

struct MyArg {
    char name[20];
    int age;
};

void *print(void *arg) {
    sleep(2);
    struct MyArg *myarg = (struct MyArg *)arg;
    printf("%s is %d years old!\n", myarg->name, myarg->age);
}

int main() {
    pthread_t tid;
    struct MyArg myarg;
    myarg.age = 18;
    strcpy(myarg.name, "Maureen");
    pthread_create(&tid, NULL, print, (void *)&myarg);
    myarg.age = 19;
    pthread_join(tid, NULL); //主线程等待子线程结束后再退出
    return 0;
}
```

编译运行的结果为：`Maureen is 19 years old!`。

原因是将18传给线程后，线程和进程的共享内存空间发生了变化，线程打印之前，age就增大了1岁。那么如何解决这个问题呢？且看下文：

5、低端解决：将数据拷贝一份

```C
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>
#include <string.h>

struct MyArg {
    char name[20];
    int age;
};

void *print(void *arg) {
    sleep(2);
    struct MyArg *myarg = (struct MyArg *)arg;
    printf("%s is %d years old!\n", myarg->name, myarg->age);
}

int main() {
    pthread_t tid;
    struct MyArg myarg;
    myarg.age = 18;
    strcpy(myarg.name, "Maureen");
    struct MyArg tmparg = myarg; //将数据拷贝一份
    pthread_create(&tid, NULL, print, (void *)&tmparg);
    myarg.age = 19;
    pthread_join(tid, NULL); //主线程等待子线程结束后再退出
    return 0;
}
```

编译运行结果为`Maureen is 18 years old!`。

但是这种方案也存在一个缺陷，且看下：

```C
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>
#include <string.h>

struct MyArg {
    char name[20];
    int age;
};

void *print(void *arg) {
    sleep(2);
    struct MyArg *myarg = (struct MyArg *)arg;
    printf("%s is %d years old!\n", myarg->name, myarg->age);
}

int main() {
    pthread_t tid;
    while (1) {
        struct MyArg myarg;
        scanf("%d", &myarg.age);
        strcpy(myarg.name, "Maureen");
        struct MyArg tmparg = myarg; //将数据拷贝一份
        pthread_create(&tid, NULL, print, (void *)&tmparg);
    }
    pthread_join(tid, NULL); //主线程等待子线程结束后再退出
    sleep(30);
    return 0;
}
```

运行结果：

![image-20201023210518842](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201023210518842.png)

不断更新输入的值，有的值并不会被打印出来，是因为tmparg是一块固定的区域，它只会放入最新输入的值，于是传递的也是在线程执行函数最近输入的值。

通常这种经常更新值的情况应该创建一个数组，这样每个元素都有自己特定的地址。

6、线程自杀

```c
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>
#include <string.h>

struct MyArg {
    char name[20];
    int age;
};

void *print(void *arg) {
    struct MyArg *myarg = (struct MyArg *)arg;
    printf("%s is %d years old!\n", myarg->name, myarg->age);
    pthread_exit(NULL);
    printf("Killed by itself!\n");
}

int main() {
    pthread_t tid;
    while (1) {
        struct MyArg myarg;
        printf("Please input:\n");
        scanf("%d", &myarg.age);
        strcpy(myarg.name, "Maureen");
        pthread_create(&tid, NULL, print, (void *)&myarg); //每次循环都会创建一个线程
    }
    pthread_join(tid, NULL); //主线程等待子线程结束后再退出
    sleep(30);
    return 0;
}
```

运行结果：

![image-20201023211850607](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201023211850607.png)

可以看到，并没有输出`Killed by itself!`这句话，因为线程已经自杀了，线程终止了，自然不会再接着打印这句话，但是其他的线程还是在正常工作。

7、线程他杀

```C
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>
#include <string.h>

struct MyArg {
    char name[20];
    int age;
};

void *print(void *arg) {
    struct MyArg *myarg = (struct MyArg *)arg;
    printf("%s is %d years old!\n", myarg->name, myarg->age);
    sleep(2);
    printf("Killed by others!\n");
}

int main() {
    pthread_t tid;
    while (1) {
        struct MyArg myarg;
        printf("Please input:\n");
        scanf("%d", &myarg.age);
        strcpy(myarg.name, "Maureen");
        pthread_create(&tid, NULL, print, (void *)&myarg);
        pthread_cancel(tid); //主线程杀掉子线程
    }
    pthread_join(tid, NULL); //主线程等待子线程结束后再退出
    sleep(30);
    return 0;
}
```

运行结果：

![image-20201023212245447](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201023212245447.png)

可见，并没有输出`Killed by others!`这句话，是因为在sleep(2)这个时间里，被主线程杀掉了，线程终止也就不会再继续往下执行了。

8、线程分离

```C
#include<stdio.h>
#include <unistd.h>
#include <pthread.h>
#include <string.h>

struct MyArg {
    char name[20];
    int age;
};

void *print(void *arg) {
    struct MyArg *myarg = (struct MyArg *)arg;
    printf("%s is %d years old!\n", myarg->name, myarg->age);
    sleep(2);
    printf("Killed by others!\n");
}

int main() {
    pthread_t tid;
    while (1) {
        struct MyArg myarg;
        printf("Please input:\n");
        scanf("%d", &myarg.age);
        strcpy(myarg.name, "Maureen");
        pthread_create(&tid, NULL, print, (void *)&myarg);
        pthread_detach(tid); //主线程就不能再join子线程了，即不能再等待子线程了
    }
    pthread_join(tid, NULL); //主线程等待子线程结束后再退出
    sleep(30);
    return 0;
}
```

运行结果：

![image-20201023212755714](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201023212755714.png)



#### 线程锁的使用

```c
#include <stdio.h>
#include <unistd.h>
#include <pthread.h>

int now;

void *print() {
    while (1) {
        if (now >= 100) break;
        now++;
        printf("%d\n", now);
    }
}

int main() {
    pthread_t tid[2];
    pthread_create(&tid[0], NULL, print, NULL);
    pthread_create(&tid[1], NULL, print, NULL);

    for (int i = 0; i < 2; i++) {
        pthread_join(tid[i], NULL); //等待子线程结束
    }
    return 0;
}
```

这个程序有时候会输出大于100个数，就需要加锁来控制：

下面这是一个死锁：

```C
#include <stdio.h>
#include <unistd.h>
#include <pthread.h>

int now;
pthread_mutex_t mutex = PTHREAD_MUTEX_INITIALIZER;
void *print() {
    while (1) {
        pthread_mutex_lock(&mutex);
        if (now >= 10000) break;
        now++;
        printf("%d\n", now);
        pthread_mutex_unlock(&mutex);
    }
}

int main() {
    pthread_t tid[2];
    pthread_create(&tid[0], NULL, print, NULL);
    pthread_create(&tid[1], NULL, print, NULL);

    for (int i = 0; i < 2; i++) {
        pthread_join(tid[i], NULL); //等待子线程结束
    }
    return 0;
}
```

死锁的原因是，当break的时候，这个锁没有释放。所以更改如下：

```c
#include <stdio.h>
#include <unistd.h>
#include <pthread.h>

int now;
pthread_mutex_t mutex = PTHREAD_MUTEX_INITIALIZER;
void *print() {
    while (1) {
        pthread_mutex_lock(&mutex);
        if (now >= 10000) {
            pthread_mutex_unlock(&mutex);
            break;
        }
        now++;
        printf("%d\n", now);
        pthread_mutex_unlock(&mutex);
    }
}

int main() {
    pthread_t tid[2];
    pthread_create(&tid[0], NULL, print, NULL);
    pthread_create(&tid[1], NULL, print, NULL);

    for (int i = 0; i < 2; i++) {
        pthread_join(tid[i], NULL); //等待子线程结束
    }
    return 0;
}
```

#### 多线程练习

多线程累加，实现一个多线程程序(源文件名multi_thread_add,c，可执行程序multi_thread_add)，并发度设置为5，也就是5个线程协同计算，计算从1累加到1000的值。

```c
#include <stdio.h>
#include <unistd.h>
#include <pthread.h>

pthread_mutex_t mutex = PTHREAD_MUTEX_INITIALIZER;
int sum = 0;
int i = 1000;

void *do_add() {
    while (i > 0) {
        pthread_mutex_lock(&mutex);
        sum += i;
        i--;
        pthread_mutex_unlock(&mutex);
    }
}

int main() {
    pthread_t tid[5];
    for (int i = 0; i < 5; i++) {
        pthread_create(&tid[i], NULL, do_add, NULL);
        pthread_join(tid[i], NULL);
    }
    printf("sum=%d\n", sum);
    return 0;
}
```

# 十五、Linux操作系统结课复习

**查找命令的方法**：

1、TAB补充命令

2、查看使用过的命令：`history`或 `ctrl+ R`

3、查询命令：man手册`man -k command`，`k`为关键字，如`man -k copy`可以找到包含copy的命令

4、`apt-cache`，如`sudo apt-cache search nmon`，查找nmon

5、百度

**命令使用方式**：

1、直接执行命令，如果需要参数会有提示 help

2、`command -h`

3、man手册或者info

4、`tldr command` （apt安装tldr会在家目录下创建一个文件夹.tldr，将github对应的内容都抓下来了，所以使用tldr的时候就相当于离线看文档，所以会比较快；而如果用pip安装的tldr，每次使用tldr命令都会到github上查找，速度比较慢）

**查看函数定义**

1、`man function_name`

2、vim中`ESC`，将光标移动到关键字的位置，通过`shift + k`查看man手册中的关键字

3、科学上网

**管道和词频统计**

管道：将上一个命令的标准输出作为下一个命令的标准输入。

标准输入输出都定义在`stdio.h`中，那么针对命令，哪些是标准输出呢?

首先，标准输出就是打印到屏幕上，而Linux中一切皆文件，所以屏幕也是一个文件，标准输出(printf)就是打印到屏幕这个文件上。Linux中，stdio中的东西都是缓冲io。屏幕上除了标准输出还可以显示标准错误。

无论是从文件还是终端读取的数据，只要需要读取文件中的内容，都是标准输入。

后面的命令是否能接收标准输入？

1、 先执行`echo "abc"`

![image-20201028112620186](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028112620186.png)

是将`abc`输出到`pts/0`这个文件中，这就是标准输出。

2、

![image-20201028113915787](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028113915787.png)

再执行`ls`，而`ls`并不会读被写入`abc`的管道文件中的内容，所以`abc`这个数据给到管道流后，`ls`并没有收，因为`ls`没有读文件的操作，只有解析字符串的操作，即`ls abc`会查看有没有这个文件存在。

3、

![image-20201028113946257](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028113946257.png)

而`echo "abc" | cat`， 本来`echo "abc"`是将`abc`输出到屏幕，但是现在接了管道，就输出到管道文件中，`cat`会读管道文件里的内容（cat功能是正向连续读），所以就读出了`abc`这个内容。

4、

![image-20201028114007730](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028114007730.png)

`echo "abc" | xargs cat`，通过`xargs`将管道流中的内容`abc`读出来作为参数给`cat`，将`abc`作为`cat`的参数，即执行的是`cat abc`，这个操作就是打开`abc`这个文件，并读取该文件中的内容。

5、`cat`如果没有参数，会从标准IO中读，即pts这个终端，从键盘输入；而`echo "abc" | cat`中的标准输入就是这个管道，所以就将`abc`读入了。

`cat`如果有参数，`cat abc`把abc读入作为参数再打开abc文件去读。

管道后面命令是否能成功执行，取决于标准输入是作为命令的参数还是命令即将要读的文件内容。

![image-20201028114708715](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028114708715.png)

因为`cat`已经有参数了，所以不会再读入管道中的内容。

6、词频统计

![image-20201028120205053](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028120205053.png)

```shell
find . -name  "*.c" | xargs cat 2>/dev/null| tr -s -c "a-zA-Z" "\n" | sort | uniq -c | sort -n -r | head -n 10
```

其中`2>/dev/null`是将cat结果的标准错误重定向到/dev/null中， /dev/null和/dev/0都是数据黑洞。



**Linux三剑客**：grep、awk（数据整理，数据分析）、sed（数据替换，查找删除）。

`grep -r maureen * -n` ：查找出现了maureen字符串的文件，并显示该字符串在文件中的行号

​	`-r`：表示递归，如果是文件夹则进入继续查找

​	`-n`:  显示出现了文件中maureen字符串所在的行号



**进程和线程**

1、fork，创建多进程，小技巧：每次fork之前给定一个标号，fork第一个就标1，fork第二个就标2。

2、exec，进程变身，exec如果成功执行那么它后面的代码是不会被执行的，如果执行失败后面的代码会执行的。

![image-20201028180118456](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201028180118456.png)

exec只有出现错误的时候才会有值返回。

3、孤儿进程：父进程死了，被1号进程收养

4、僵尸进程：不会再使用系统资源，但是本身占用的资源是不会释放的。

5、守护进程：一直在，守护的是一个服务。可能涉及到线程池。守护进程是孤儿进程，通过IO感知。底层提供了什么样的服务能让线程感知到任务来。查看守护进程：xxxd类型的服务就是守护进程。

6、进程的自杀和他杀。kill提供的信号查看方式：`kill -l`

![image-20201029102513505](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201029102513505.png) 

进程对信号的处理方式有三种：

1）、程序中自定义了信号处理函数：收到信号要做什么事，涉及到的函数为`signal`。

```c
#include<stdio.h>
#include <unistd.h>
#include <sys/types.h>
#include <signal.h>

void print(int signum) {
    printf("Bye!\n");
}

int main() {
    signal(SIGINT, print);
    while (1) {
        sleep(10);
    }

    return 0;
}
```

执行程序，按`ctrl+c`会打印出`Bye`，正常情况下按`ctrl+c`会发出`SIGINIT`这个信号强制中断，但是因为程序注册了一个信号处理函数，所以并不会中断程序，而只是打印出`Bye`。

使用用户自定义信号`kill -10`终止程序：

![image-20201029103340425](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201029103340425.png)

用户自定义信号的默认操作都是杀死进程。

7、线程读写操作都要加锁，读之所以加锁是为了确保没有人在写，否则读到的数据就不正确了。线程之间是共享数据的。线程的互斥->死锁。

8、同步：事件发生顺序是受约束的。线程同步：访问资源的时候按照一定的顺序/规则去访问。

​	拓展（自学）：线程安全 -- 标准IO是线程安全的吗？

9、程序->进程->线程（可自学）



**主函数的返回值问题**

```C
#include<stdio.h>

int main() {
    return 256;
}
```

编译运行：

![image-20201029104946930](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201029104946930.png)

运行结果为0。

而：

```C
#include<stdio.h>

int main() {
    return -1;
}
```

编译运行后的结果：发现返回值为255

![image-20201029105127081](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201029105127081.png)

那这个现象是怎么产生的呢？

答：主函数的返回值会转成一个`uint8_t`类型的数

```C
#include <stdio.h>
#include <unistd.h>
#include <inttypes.h>

int main() {
    uint8_t a;
    for (a = 0; a < 256; a++) { //这是一个死循环，因为a的最大值为2^8 = 255，该条件会一直满足,当a = 255，之后再a++，a = 0
        printf("a = %" PRId8 "\n", a);
        usleep(10000);
    }
    return 0;
}
```

```C
#include <stdio.h>
#include <unistd.h>
#include <inttypes.h>

int main() {
    uint8_t a;
    printf("%d\n", (uint8_t)(-1)); //输出结果为255
    return -1;
}
```

之所以操作系统将主函数返回值设置为`uint8_t`类型(0~255)，是为了提升程序之间交互的便利性，程序之间是互相调用的。



**字符串的输出格式**

```C
#include<stdio.h>
#include <unistd.h>

int main() {
    char a[100] = "abcdefg";
    printf("%5s1\n", a);
    printf("%15s1\n", a);
    printf("%.2s1\n", a);
    printf("%10.2s1\n", a);
    return 0;
}
```

运行结果：

![image-20201029111504553](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201029111504553.png)

- `printf("%5s1\n", a);` : 输出5个字符的宽度，但是字符串是大于5个字符宽度的，于是全部输出；`1`的意义是字符串的输出以`1`结尾。
- `printf("%15s1\n", a);`：占15个字符的宽度，不足的用空格在前面补足。
- `printf("%.2s1\n", a);`：`.`为字符串开始的位置，`2`表示要输出字符串从头开始的两个字符。
- `printf("%10.2s1\n", a);`：`10`为在字符串输出之前，先输出10个空格；`.`为字符串开始的位置；`2`表示输出字符串从头开始的2个字符。



# 练习题

## 1、求文件中的最长字符串(shell)

```shell
#!/bin/bash

max_len=0
max_string=''

#判断输入的参数个数是否小于1
if [[ $# -lt 1 ]];then
    printf "Usage: %s file[...]\n" $0
fi

#输出参数，$*为参数的总数
for i in $*;do
    echo $i
done

#遍历文件中的字符串 ``中的操作是将文件中非a-zA-Z的字符替换为空格并压缩
for i in `cat $1 | tr -s -c "a-zA-Z" " "`;do
    len=${#i}
    if [[ $len -gt ${max_len} ]];then #查找最大长度及最大长度的字符串
        max_len=$len
        max_string=$i
    fi
done

echo $max_string $max_len
```

运行结果：

```shell
#输出Prime2.sh文件中的最长字符串及其长度
lj@Aliyun test % bash find_max_string_one_file.sh  Prime2.sh                                                     
Prime2.sh
function 8
```



```shell
#输出"abc"字符串在file中的位置-行号
grep -n "abc" file  
```

获取HOME变量的字符串长度：2种方式

```shell
echo -n $HOME | wc -c
```

```shell
echo ${#HOME}
```



## 2、找出最长的三个字符串（shell)

> Usage: bash find_string.sh  /home/suyelu

1. 文件名：`find_string.sh`

2. 参数说明：

    1. 如果没有参数，则使用**缺省参数**：`.`
    2. 如果有参数，则可以是目录，也可以是文件
    3. 也可以是多个参数，文件，目录都可，也可混合

3. 作用：

    1. **遍历**参数中**所有目录**和**文件**，找到最长的三个字符串:只包含`[a-zA-Z]`的字符串
    2. 如果是目录，需要对目录`递归`操作
    3. 不能忽略隐藏文件
    4. 对于`不是普通文件`的文件，应该直接跳过

4. 输出样式：

  ```bash
/home/suyelu/a.txt:2   abcdefghj 9
./b.txt:12  abcdef 6
./.vimrc:34  SHELL 5
  ```

    1. 每一行为：`文件名:行数 字符串	长度`

> **小提示**:如果你不知道应该关注什么文件，可以试试`file`，这个命令，看看有什么惊喜发现



查找最长的字符串的做法：

- function.sh: 将涉及到的功能封装成函数

```shell
#!/bin/bash

filter_types=(mp4 avi gz zip tar) #定义过滤器，这些类型的文件会被过滤，黑名单

function filter(){
    file_name=$1
    typename=`basename ${file_name} | rev | cut -d "." -f 1 | rev` #rev将字符串逆序，此处即文件名逆序
    for i in ${filter_types[@]};do #@获取所有的值
        if [[ ${typename} == ${i} ]];then               #判断文件后缀
            echo "Filters On! ${file_name}"
            return 1
        fi
    done
}

function find_max_string_in_file(){ #从文件中查找最长的字符串
    if [[ ! -f ${1} ]];then  #判断是否为普通文件
        echo "$1 is not a regular file!"
        return
    fi
    filter $1 #调用函数filter
    if [[ $? -eq 1 ]];then  #$?上一条命令(filter $1)的返回值
        return
    fi
    echo "Finding Max_String in file $1"
    words=`cat $1 | tr -s -c "a-zA-Z" "\n"` #获取到一个文件中的所有字符串
    for i in ${words};do
        len_t=`echo -n ${i} | wc -c`   #获取到每个字符串的长度
        if [[ ${len_t} -gt ${len_max} ]];then
            len_max=${len_t}
            max_string=${i}
            max_file=$1
        fi
    done
}

function find_max_string_in_dir(){ #从目录中(如果是目录递归查找)的文件中查找最长的字符串
    for i in `ls -A $1`;do #ls -A $1获取到传入的目录中的目录和文件，-A去掉当前目录和上级目录
        if [[ -d ${1}/${i} ]];then  #如果是个目录
            echo "${1}/$i is a dir"
            find_max_string_in_dir ${1}/${i}
        else
            echo "${1}/${i} is a file"
            find_max_string_in_file ${1}/${i}
        fi
    done
}
```

- find_string.sh: 引入function.sh，使用其中的函数

```shell
#!/bin/bash
len_max=
max_string=""
max_file=""

source function.sh  #导入function.sh，类似于include的作用

if [[ $# -eq 0 ]];then
    find_max_string_in_dir "." #如果没写参数，就在当前目录进行查找操作
else
    for i in $@;do   #$@ 所有参数
        if [[ -d $i ]];then  #如果是目录
            find_max_string_in_dir $i
        else
            find_max_string_in_file $
        fi
    done
fi
#\033[31;34m %s \033[0m 给%s换颜色
printf "The max string is \033[31;34m %s \033[0m , with length \033[31;34m %d \033[0m in file \033[31;34m %s \033[0m\n" $max_string $len_max $max_file
```

运行测试： 当前目录下的文件信息

![image-20201015123205933](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015123205933.png)

![image-20201015123252486](Linux%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%85%A5%E9%97%A8%E4%BD%BF%E7%94%A8.assets/image-20201015123252486.png)

上面的代码只能完成查找最长的一个字符串，要找出最长的三个字符串需要自己思考如何处理。



## 3、自动完成环境准备工作(shell)

> 大家都经历过环境准备工作，繁琐的手动操作，总容易出错，但是为了锻炼大家的实操能力，不得不让大家一步一个坎的自己去尝试，现在，你已经学了`shell`编程，请你按照群里的文档，将环境准备工作用`bash`脚本完成吧

1. 文件名：bash do_env.sh username (**username  是新添加的用户名**)
2. 请你在root用户下执行该脚本
3. 该脚本中，不涉及`shell`的切换
4. 可保留脚本中的交互过程
5. 对于某些耗时的操作，你可以通过输出日志的方式，模拟完成，比如，vim的配置耗时较长，那你就不真的操作，只输出一句`“我现在正在配置vim”`即可

> 配置过程中，新加的用户，你可以用`userdel -r username`命令删除用户重新开始
>
> 当然，添加用户的命令，你也可以尝试用`useradd` + `passwd`来做，而非`adduser`



## 4、实现简单的ls （C语言实现）

1. 实现简单的<span style="color:red">`ls`</span>

    1. 可以有<span style="color:red">`0`</span>个到 <span style="color:red">`多个`</span>参数
    2. 参数可以是文件，也可以是目录；
    3. 如果没有参数，使用缺省的<span style="color:red">`.`</span>;
    4. 输出每个目录下所有的文件名；
    5. 如果参数是文件，则只输出文件名；

    > 具体显示样式，可以参考<span style="color:red">`ls`</span>命令

```C
/*************************************************************************
	> File Name: 1.ls.c
	> Author: suyelu
	> Mail: suyelu@126.com
	> Created Time: Thu 15 Oct 2020 06:51:47 PM CST
 ************************************************************************/

#include <stdio.h>
#include <unistd.h>
#include <sys/types.h>
#include <dirent.h>
void do_ls(const char *);
int dir_num = 0;
int main(int argc, char **argv) {
    dir_num = argc;
    if (argc == 1) {
        do_ls(".");
    } else {
        for (int i = 1; i < argc; i++) {
            do_ls(argv[i]);
        }
    }
    return 0;
}

void do_ls(const char *name) {
    DIR *dir = NULL;
    struct dirent *direntp;
    if ((dir = opendir(name)) == NULL) {
        if (access(name, R_OK) == 0) {
            printf("%s ", name);
        }
    } else {
        if (dir_num > 2) printf("%s:\n", name);
        while ((direntp = readdir(dir))) {
            printf("\033[31;34m%s\033[0m ", direntp->d_name);
        }
        printf("\n");
    }
    return ;
}
```

## 5、实现自己的Shell （C语言实现）

> 具体样式模拟`bash`或者`zsh`,可以做细节上的优化

1. 具有**内置命令**`cd`、`pwd`
2. 可以调用绝大多数系统命令
3. 支持文件重定向`>` 和 `<`

> 文件的打开，目录的切换；
>
> 进程创建，`fork`, `exec`,`system`,`popen`,`pclose`



