---
title: Git指令整理
date: 2018-05-02 15:30:00
# tags:  "Git"
# type: "categories"
comments: true
---

# Git入门

## Git 常用指令

#### 本地repo关联git

    git init
    git commit -m 'init'
    git remote add origin git@github.com:xxx/xxx.git
    git push -u origin master

#### 拷贝远程的Git repo到本地

    git clone git@github.com:xxx/xxx.git

#### 将修改的本地文件提交到git

    git status —— 查看一下状态
    git diff —— 查看具体修改了什么内容 (可省略，自己改的东西心理应该都有数..)
    git add -A —— 提交所有发生状态变化的文件
    git commit -m 'xxxx' 
    git pull —— 以防冲突（当你提交时，发现其他人已经提交的内容时）
    git push

#### 查看commit日志

    git log