---
layout: "post"
title: "git-notes-tag"
date: "2016-06-27 10:01"
---

# 标签既是快照，嗯，就是备份

# 创建标签（commit-id 默认为HEAD）
> git tag tag-name commit-id

# 创建标签
> git tag -a tag-name -m "discription" commit-id

# 查看标签
> git tag

# 查看标签信息
> git show tag-name

# 删除标签
> git tag -d tag-name

# 删除远程仓库标签
> git push origin :refs/tags/tag-name
