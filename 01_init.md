# 01.git-learn

>第一次提交github

## Build Setup

``` bash
1.git init # 初始化本地master
2.git add .  # 文件修改、文件新建，添加暂存区。
  gti add -u # 文件修改、文件删除，添加暂存区。(已经追踪的文件)
  git add -A # 所有的修改，添加暂存区。
3.git commit -m '提交描述' # -a参数将所有已跟踪文件中的执行修改或删除操作的文件都提交到本地仓库
4.git remote add origin https://github.com/LTAND/git-learn.git # 创建远程库别名为origin
5.git push -u origin master # 将master分支推送远程库origin
```