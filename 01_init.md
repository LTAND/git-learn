# 01.第一次提交github

>git-learn

## Build Setup

``` bash
git config --global user.name "Your Name"
git config --global user.email "email@example.com"

# 初始化本地master
1.git init 

2.git add .  # 文件修改、文件新建，添加暂存区。

  gti add -u # 文件修改、文件删除，添加暂存区。(就是已经追踪(push)的文件)

  git add -A # 所有的修改，添加暂存区。

# -a参数将所有已跟踪文件中的执行修改或删除操作的文件都提交到本地仓库
3.git commit -m '提交描述' 

# 创建远程库别名为origin
4.git remote add origin https://github.com/LTAND/git-learn.git 

# 将master分支推送远程库origin
5.git push -u origin master
```