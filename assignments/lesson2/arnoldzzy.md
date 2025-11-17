# Git工具安装与使用报告

## 学员GitHub用户名: arnoldzzy

## 1. Git安装过程

### 1.1 访问并下载安装包，安装到本地 

https://git-scm.com/install/windows

choose "Git for Windows/x64 Setup"

### 1.2 操作系统

Windows 11 Home
64-bit operating system, x64-based processor

## 2. 遇到的问题及解决方法

### 2.1 无法访问Github以及加载下载过慢

- 修改本地hosts文件
安装Watt Toolkit加速器from Microsoft Appstore

- 安装Dev-sidecar
https://github.com/docmirror/dev-sidecar/releases/tag/v2.0.0

大多数情况下Dev-sidecar好用，下载时用Edge比Chrome快。

### 2.2 不懂如何安装，配置以及应用git bash

- 阅读文献
https://git-scm.com/book/en/v2/

- 问AI

## 3. 版本信息截图
<img width="358" height="212" alt="image" src="https://github.com/user-attachments/assets/456c6550-22e2-4e99-a6ea-cd92a6b83096" />

## 4. Git命令使用过程总结

### 4.1 新增
- git config --global user.name/user email: 配置用户并和email
- cd：定位到要操作的目录，操作成功后地址后会出现（master）
- git init: 创造.git文件，记录库文件的版本变化
- git branc -a： 查看本地及远程所有分支
- git status: 查看仓库改动后的状态，全局
- git diff: 比较仓库改动后的状态，局部
- git commit -m “text”： 提交文件和text到本地仓库，无需打开编辑器
- git rm: git add的reversal

### 4.2 原有
（在此处总结使用Git命令的过程，包括但不限于以下操作：
- git clone: 克隆远程仓库到本地
- git add: 添加文件到暂存区
- git commit: 提交更改到本地仓库,**需要打开编辑器**
- git push: 推送更改到远程仓库
- git pull: 从远程仓库拉取最新更改
等其他相关命令的使用体验和理解）
