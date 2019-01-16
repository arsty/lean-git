1、初始化git，用户名，邮箱：
	`git config --global user.name "Your Name"`
	`git config --global user.email "email@example.com"`

2、配置SSH密钥：
	在.ssh目录下，进入Git Bash:  `ssh-keygen -t rsa -C "youremail@example.com"`，创建两个文件
	复制id_rsa.pub中的key到GitHub上

3、初始化本地仓库使用：`git init`

4、把所有文件都添加到暂存区：`git add -A`

5、添加具体文件到暂存区：`git add 文件名.后缀名 文件名.后缀名`

6、把暂存区的文件提交到仓库： `git commit -m "描述"`

7、把本地仓库与远程仓库向关联：git remote add origin 仓库地址,如:`git@github.com:arsty/acs.git`
也可以直接`git clone 仓库地址`，进行关联

8、把本地仓库推送到远程仓库：`git push`

9、若第一次推送需要使用：`git push -u origin master`

P.s: origin是远程仓库的名称，Git默认的叫法，可以改为别的
