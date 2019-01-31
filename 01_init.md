# 01.git-learn

>第一次提交github

## Build Setup

``` bash
1.git init # 初始化本地master
2.git add .  # 监控工作区的所有文件变化(文件内容修改,新文件,但不包括被删除文件),提交到暂存区
  gti add --update || -u # 监控已经被add的文件,将被修改的文件提交到暂存区
  git add -all || -A # 以上功能的结合
3.git commit -m '提交描述' 
4.git remote add origin https://github.com/LTAND/git-learn.git # 创建远程库别名为origin
5.git push -u origin master # 将master分支推送远程库origin
```