# 02.追加提交，在不创建新的commit_id

> git commit -amend -m '提交' 

```bash
# 撤销之前commit操作
git add 222.txt
git commit -m '错误的信息'
git commit --amend -m '正确的信息'

# commit 错漏新文件
git add old.txt
git commit -m 'add new.txt'
git add new.txt 
git commit --amend -m 'add new.txt'
```
