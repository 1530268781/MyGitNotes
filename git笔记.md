# Git基础命令

## 1.设置签名

### （1）项目级别/仓库级别：

仅在当前本地库范围内有效

- #### 设置用户名	<font color='red'>git config --global user.name 'zlx1530268781'</font>

- #### 设置用户邮箱 <font color='red'>git config --global user.email '1530268781@qq.com'</font>

- #### 查看设置        <font color='red'>git config --list</font>

信息保存位置：./.git/config 文件



### （2）系统用户级别：

登录当前操作系统的用户范围

- #### <font color='red'>git config user.name ‘用户名’</font>

- #### <font color='red'>git config user.email  ‘邮箱’</font>

<font color='cornflowerblue'>注意：这里设置的签名和登录远程库(代码托管中心)的账号、密码没有任何关 系。 </font>

## 2.创建一个Git仓库

- ### 	新建一个文件夹		<font color='red'>mkdir demo</font>

- ###     进入这个目录            <font color='red'>cd demo</font>

- ###     初始化（创建git仓库）<font color='red'>git init</font>    ==会生成一个.git隐藏文件==

## 3.Git工作区域

<img src="git笔记.assets/image-20210418162656580.png" alt="image-20210418162656580" style="zoom:50%;" />

- #### 查看工作区、暂存区状态：<font color='red'>git status</font>

## 4.向仓库添加文件

- ### 创建一个文件       <font color='red'>touch  test1.txt</font>

- ### 添加到git暂存区    <font color='red'>git add test1.txt</font>

- ### 提交操作             <font color='red'>git commit -m '提交描述'</font>  ==只是提交到本地仓库==



## 5.修改文件

- ### 修改文件后，按照添加文件的步骤commit即可




## 6.删除文件

- ### 删除一个文件   <font color='red'> rm  test1.txt</font>

- ### 从git中删除    <font color='red'>git rm test1.txt</font>

- ### 提交操作       <font color='red'>git commit -m '提交描述'</font>

  

## 7.Git远程仓库

- ### 提交到远程仓库    <font color='red'>git  push  origin  master</font>



## 8.克隆远程仓库到本地

- ### <font color='red'>git  clone 仓库地址</font>



## 9.查看历史记录

- #### git log

- #### git log --pretty=oneline

- #### git log --oneline