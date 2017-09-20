http://blog.jobbole.com/78960/

https://git-scm.com/book/zh/v2/Git-%E5%9F%BA%E7%A1%80-%E8%AE%B0%E5%BD%95%E6%AF%8F%E6%AC%A1%E6%9B%B4%E6%96%B0%E5%88%B0%E4%BB%93%E5%BA%93


1.拉取远程分支并创建本地分支： 
git checkout -b 本地分支名x origin/远程分支名
git fetch origin 远程分支名x:本地分支名x

2.删除远程分支： git push origin --delete Su-modify 3.

3.如果并不想让远程仓库上的分支叫做 serverfix，可以运行 git push origin serverfix:awesomebranch 来将本地的 serverfix 分支推送到远程仓库上的 awesomebranch 分支。
