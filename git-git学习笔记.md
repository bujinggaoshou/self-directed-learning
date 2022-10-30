



git配置远程地址

git remote add origin url ，其中url为远程仓库地址。

git删除远程地址

git remote rm origin

查看远程仓库地址信息

git remote -v 



初始化git

　　$git init

四、将文件添加到本地仓库

　　$git add --all

五、提交到本地仓库

　　$git commit -m "首次提交"

六、与GitHub上的分支建立链接

　　$git remote add origin https://github.com/*****/shop.git

七、将刚刚提交的文件推送到GitHub上

　　$git pull --rebase origin master

　　$git push -u origin master -f