Git 本地项目与远程项目进行关联

1.需要先创建一个远程项目仓库，用于存放项目

2. 本地配置 Git 配置  
    $ git config --global user.name “Your Name”
  $ git config --global user.email "email@example.com"

3.进入本地创建的项目，进行项目初始化
git init 项目初始化
git status 查看本地目录状态信息

4.将本地项目与 GitHub 上项目进行关联
git remote add origin http://xxxxx 项目地址

5.准备在项目上传时可以先更新一下项目，避免项目代码出现冲突
git pull --rebase origin master

6.提交代码
git add .
git commit -m "注释信息"
git push -u origin master

7.推送代码到远程，可能有冲突，强制覆盖原有的分支
git push -u origin master -f 覆盖不会丢失代码
