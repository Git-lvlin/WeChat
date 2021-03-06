## 工作区

## 初始化版本库
- git init(第一次需要)

## 提交到暂存区
- git add 文件名
- git add . 将所有变动提交到缓存区

## 提交到本地仓库
- git commit -m '注释'

## 查看状态
- git status (辅助命令)
- 查看工作区和暂存区的状态

## 查看日志
- git log 查看完整日志
- git reflog 查看简单日志

## 版本回退
- git reset --hard HEAD^ 回退到上一个版本
- git reset --hard 版本号 回退到指定版本
- 注意把当前代码先提交到本地仓库
- 工作区的代码自动变成恢复的指定版本

## 查看变动
- git diff 文件名
- 会列出该文件前后的差异

## 全局配置
-  git config --global user.name "你的git名称"
-  git config --global user.email "你的git验证邮箱"
-  查看配置列表： git config --list

## 创建远程仓库
- 进入GitHub官网
- 创建一个新的远程从仓库

## 创建项目
- https://github.com/Git-lvlin/WeChat.git 项目的仓库地址

## 将本地仓库与远程仓库关联
- git remote add origin 你的远程仓库地址
- git remote -v 查看本地仓库关联的远程仓库地址

## 将本地仓库提交到远程仓库
- git push -u origin master 第一次提交远程
- git push 将本地仓库提交到远程仓库
- u origin master 设置默认的提交地址和分支

## 正常提交（非第一次）
- git add . 提交暂存区
- git commit -m '注释' 提交到本地仓库
- git pull 先更新远程到本地
- git push 提交到远程仓库 (默认提交到origin上的master分支)

## 修改关联的远程仓库地址
- git remote rm origin
- git remote add origin ssh地址

## 更新代码
- 确保自己工作区的代码先提交到本地仓库
- 然后再从远程更新到本地 git pull
- git clone 远程仓库地址  克隆代码到本地
 
##分支操作
- git branch  查看当前所有分支
- 当前分支名前有个星号
- git branch 分支名  创建一个分支
- git checkout 分支名 切换分支
- git merge 分支名  合并某分支到当前分支
- git branch -d 分支名  删除某分支
- git push origin 分支名  将某个分支提交到远程仓库
- git pull origin 分支名  将某个分支更新到本地仓库

##忽略列表
- 在项目中创建文件 .gitignore
- 把不需要提交到远程仓库的文件或目录写在忽略列表中
## test分支
.....
