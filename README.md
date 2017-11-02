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
