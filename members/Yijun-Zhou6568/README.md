\# Yijun-Zhou6568 Chapter0 作业

\## Git基础学习笔记

\### 1. Git是什么

Git是分布式版本控制系统，可以记录文件每一次修改，随时回退历史版本、多人协同开发。



\### 2. 常用基础命令

1\. `git init`：初始化本地git仓库

2\. `git clone 仓库地址`：克隆远程仓库到本地

3\. `git status`：查看当前仓库状态

4\. `git add .`：把所有修改加入暂存区

5\. `git commit -m "备注信息"`：提交暂存区内容到本地仓库

6\. `git branch`：查看本地分支

7\. `git checkout -b 分支名`：创建并切换到新分支

8\. `git push`：把本地分支推送到远程仓库

9\. `git pull`：拉取远程最新代码到本地



\### 3. 工作流程

本地修改文件 → git add加入暂存 → git commit本地保存 → git push上传到GitHub远程仓库



\### 4. 分支作用

主分支main保存稳定代码；新建分支用来写作业/开发新功能，写完之后提交Pull Request合并回主分支，不会破坏原有代码。



