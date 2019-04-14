# wechat
wechat
防撤回了解一下
3步走：
1、git init
2、git add 文件
3、git commit -m “备注”
先关联远程仓库和本地仓库：git remote add origin git@github.com:lrh4653/wechat.git
尝试push，若fatal，就git pull --rebase origin master 把本地和远程的差距补上
然后在 git push -u origin master
