#### config
**列出所有变量**
 - $git config -l

**列出全局变量**
 - $git config -l --global

**core.quotepath设为false的话，就不会对0x80以上的字符进行quote**
 - $git config --global core.quotepath false

#### rm

**撤销对已跟踪文件的跟踪，在git中删除这个文件的跟踪记录，目录加-r选项**
 - $git rm --cached FILENAME
 - $git rm -r --cached FILEFOLDER
 
 ***例如***
 - $git rm -r --cached /.gradle

#### 跟踪远程分支

 - $git branch --set-upstream-to=origin/master master

#### 删除远程分支

 - $git push origin :\<branchName\>

相当于把空的本地分支推送到远程分支，即删除远程分支

#### cherry-pick 把某些提交的捡到当前分支

```git cherry-pick 6a498ec --no-commit```

#### pull 的完整形式
```
git pull origin dev:dev
```

呃，暂不知道冒号前后哪个是远程分支的分支名
