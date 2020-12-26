---
layout: post # 使用的布局（不需要改）
title: Linux Vim Shell # 标题
subtitle: #副标题
date: 2020-12-23 # 时间
author: Nuo Xu # 作者
header-img: #这篇文章标题背景图片
catalog: true # 是否归档
tags: #标签
---

## Introduce

vi 是个文本编辑器，所有 UNIX Like 系统都会内置这个编辑器  
vim 是 vi 的强加版，其具有程序编辑的能力，可以主动以字体颜色辨识语法的正确性。

## Vim 常用命令

`vim` <file.name> 用 vim 打开文件  
`i` 进入编辑模式  
`esc` 退出编辑模式  
`:q` 退出 vim  
`:q!` 不保存文件并退出 vi  
`:wq` 保存并退出 vim

## Linux 常用命令

[Linux top 50 command](https://gywbd.github.io/posts/2014/8/50-linux-commands.html)  
[Linux Command 菜鸟教程](https://www.runoob.com/w3cnote/linux-common-command-2.html)

`ls` (list)查看当前目录下的文件  
`cd` (change directory)切换目录，~ home 目录  
`pwd` 当前工作目录路径  
`mkdir` <directory_name>创建文件夹  
`rm` 删除一个目录中的一个或多个文件或目录  
`mv -i file1 file2` 将文件名 file1 重命名为 file2，如果 file2 存在则提示是否覆盖，注意如果使用-f 选项则不会进行提示  
`cat file1 file2` 可以一次查看多个文件的内容，此命令会先打印 file1 的内容，然后打印 file2 的内容  
`chmod` 用于改变文件和目录的权限

## 怎么写 shell scprits 文件

1.第一行 `#!/bin/bash` 在宣告这个 script 使用的 shell 名称  
2.程序内容的说明：整个 script 当中，除了第一行的『 #! 』是用来宣告 shell 的之外，其他的 # 都是『注解』用途

想要运行一个名为 start.sh 的文件：  
1.`chmod +x start.sh`给这个文件运行的权限  
2.`./start.sh`运行该文件
