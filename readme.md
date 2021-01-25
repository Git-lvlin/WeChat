## 工作区

## 初始化版本库
- git init(第一次需要)

## 提交到暂存区
- git add 文件名
- git add . 将所有变动提交到缓存区

## 提交到本地仓库
- git commit -m '注释'

## 查看状态
- git status
- 查看工作区和暂存区的状态

## 查看日志
- git log 查看完整日志
- git reflog 查看简单日志

## 版本回退
- git reset --hard HEAD^ 回退到上一个版本
- git reset --hard 版本号 回退到指定版本
- 注意把当前代码先提交到本地仓库
- 工作区的代码自动变成恢复的指定版本