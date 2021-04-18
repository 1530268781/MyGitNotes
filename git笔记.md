# Git基础命令

## 1.Git基础设置

- ### 设置用户名	<font color='red'>git config --global user.name 'zlx1530268781'</font>

- ### 设置用户邮箱 <font color='red'>git config --global user.email '1530268781@qq.com'</font>

- ### 查看设置        <font color='red'>git config --list</font>

## 2.创建一个Git仓库

- ### 	新建一个文件夹		<font color='red'>mkdir demo</font>

- ###     进入这个目录            <font color='red'>cd demo</font>

- ###     初始化（创建git仓库）<font color='red'>git init</font>    ==会生成一个.git隐藏文件==

## 3.Git工作区域

<img src="git笔记.assets/image-20210418162656580.png" alt="image-20210418162656580" style="zoom:50%;" />



## 4.向仓库添加文件

- ### 创建一个文件       <font color='red'>touch  test1.txt</font>

- ### 添加到git暂存区    <font color='red'>git add test1.txt</font>

- ### 提交操作             <font color='red'>git commit -m '提交描述'</font>



## 5.修改文件

### 修改文件后，按照添加文件的步骤commit即可



## 6.删除文件

- ### 删除一个文件   <font color='red'> rm  test1.txt</font>

- ### 从git中删除    <font color='red'>git rm test1.txt</font>

- ### 提交操作       <font color='red'>git commit -m '提交描述'</font>