---
layout: "post"
title: "git-notes"
date: "2016-06-26 23:53"
---

# 初始化仓库
> git init

# 提交到仓库
> git add file1<br>
> git add file2<br>
> git commit -m "提交了一个小内容哟！"

# 实时监测仓库的变动,查看文件有没有被修改过
> git status

# 掌握详细的变动，查看文件被修改的详细内容
> git diff

# git日志，掌控所有的提交记录，以便回溯到某个版本
> git log <br>
> git log --pretty=oneline //简化输出结果

# 版本回溯
> git reset --hard  head~n //回溯n个版本><br>
> git reflof //取得每一次执行的git命令,可以方便的找到所有的commit id
> 包括回溯之后属于“未来”的commit id

# 丢弃修改
## 1,内容还没有add到暂存区,版本返回的状态是上一次commit之后或add之后的状态
> git checkout -- file


## 2,内容add到暂存区
> git reset HEAD file//把暂存区的内容放回工作区
> git checkout -- file


# 删除操作
>git rm file //从版本库中删除文件，不可恢复

- 如果不小心误删文件，可以使用以下命令恢复
> git checkout -- file
