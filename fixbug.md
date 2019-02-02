# fixbug branch

>修改bug流程

```bash
$ git stash --all # 将工作区内容临时储存
$ git checkout -b fixbug
$ git pull origin master || git reset HEAD^^ -soft(仅仅移动HEAD) -mixed -hard(包括工作区)
  git checkout master
  git merge fixbug
  git branch -d fixbug
$ git add -A
  git commmit -m 'fixbug v1.0231'
  git push origin master 
  git checkout dev
  git stash pop
  
```
