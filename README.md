# S2JQuery--作业提交
------

## [Git学习直通车](https://backlog.com/git-tutorial/cn/intro/intro1_1.html)
=============================

> 以下是指令操作，界面化操作可能更加通俗易懂，自行了解

> * git status（查看本地分支文件信息，确保更新时不产生冲突）
> * git checkout – [file name] （若文件有修改，可以还原到最初状态; 若文件需要更新到服务器上，应该先merge到服务器，再更新到本地）
> * git branch（查看当前分支情况）
> * git checkout remote branch (若分支为本地分支，则需切换到服务器的远程分支)
> * git pull (git pull origin master)

### 操作提示（谨慎操作）
> * 第一步：查看当前的git仓库状态，可以使用git status
    git status
    
> * 第二步：更新全部
    git add *
    
> * 第三步：接着输入git commit -m "更新说明"
    git commit -m "更新说明"
    
> * 第四步：先git pull,拉取当前分支最新代码
    git pull
    
> * 第五步：push到远程master分支上
    git push origin master
