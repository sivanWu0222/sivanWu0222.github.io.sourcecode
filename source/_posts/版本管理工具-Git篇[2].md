---
title: 版本管理工具-Git篇[2]
date: 2017-07-01 19:23:14
tags:
  - git
  - GitHub
  - 版本管理工具
share: true
categories:
  - git
  - 入门
reward: true
comment: true
top: 2
---

# git基本指令



## 使用git配置用户信息

> 对于git所用到的用户信息，对于我们每次提交更新来说都很重要，用来区分谁提交了更新，将会随着更新的内容纳入仓库记录中

### 配置用户名称和邮箱

> 当我们要配置用户名称的时候，都想要知道，之前是否已经配置过用户名称，如果没有配置过或者配置的不正确，将要采用如下方法进行配置


    git config user.name        //打印当前用户名称
    git config user.email       //打印当前用户邮箱
    
#### 针对全局进行配置

> 针对全局进行配置，我们的Git主配置文件将会被修改，采用 --global 选项，更改的配置文件就是位于用户主目录下的那个，以后所有的项目都会默认使用这里配置的用户信息


    git config --global user.name  "这里写上你的用户名称"
    git config --global user.email "这里写上你的邮箱"

#### 针对某个项目进行配置

> 不采用 --global 选项，就是针对某个特定的项目进行配置，而不是全局配置

    git config --local user.name "这里写上你的用户名"
    git config --local user.email "这里写上你的邮箱"


<!-- more -->

----------


## 修改默认的文本编辑器

> 如果我们在输入一些额外信息的时候，将会调用操作系统指定的编辑器，如果我们想要修改编辑器（这里假设修改为 emacs），可以采用如下指令

    git config --global core.editor emacs
    


----------


## 查看用户配置信息

> 对于一些忘记自己目前Git配置信息的用户，可以使用如下指令进行查看

    git config --list


----------


## 差异分析工具

> 在产生代码冲突的时候，我们将会决定需要使用哪种差异分析工具来解决代码冲突，可以采用如下指令修改默认的差异分析工具

    git config --global merge.tool vimdiff


----------

## 采用git获取帮助

> 在采用git指令时，难免会产生很多疑问，可以采用如下的几个指令进行查看

    git help <verb>
    git <verb> --help



## 从远程仓库克隆项目到本地

> 对于git，如何将代码从GitHub克隆到本地，非常简单，只要在联网的情况下，使用下面几个指令便可以将仓库克隆到本地

### 初始化仓库所在的目录

    git init

> 使用git init 指令，将会在当前目录生成一个.git目录

#### 没有生成 .git 目录时

> 关于很多人使用git init指令，但是没有产生.git文件，将会给我们造成很大的干扰，采用如下方法进行查看

使用 ls -la 指令进行查看，如果显示出的文件有 .git 文件，则正常

### 使用git clone指令对远程仓库克隆到本地

    git clone <url>(项目地址)
    git clone <url>(项目地址)  文件名称     
    //创建一个指定的文件夹（名称为文件名称），并将远程仓库所有代码存放到改文件夹下
    
    

