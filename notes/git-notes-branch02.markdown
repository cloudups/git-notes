---
layout: "post"
title: "git-notes-branch0"
date: "2016-06-27 09:27"
---

# 查看远程仓库的信息
> git remote -v

# 获取远程仓库内容
> git pull

# 推送到远程仓库
> git push origin branch-name

# 本地创建和远程分支对应的分支
> git checkout -b branch-name origin/branch-name

# 建立本地分支和远程分支的联系
> git branch --set-upstream branch-name origin/branch-name
