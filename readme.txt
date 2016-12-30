1. touch <file>
2. git add . or git add <file>
3. git commit -m 'description'
4. git status -s
5. add test content

#log help
#$ git log --pretty=oneline
#d40f4df16a210c4104c6deae5102950bcd034c71 readme.txt commit 2
#97aaf29afc2cbd0142226213f75f2ada90697cb0 readme.txt commit
#

#git reflog
#d40f4df HEAD@{0}: commit: readme.txt commit 2
#97aaf29 HEAD@{1}: commit (initial): readme.txt commit

$ git reflog
73930ab HEAD@{0}: commit: help content
d40f4df HEAD@{1}: commit: readme.txt commit 2
97aaf29 HEAD@{2}: commit (initial): readme.txt commit

$ git reset --hard 97aaf29
HEAD is now at 97aaf29 readme.txt commit

$ cat readme.txt
1. touch <file>
2. git add . or git add <file>
3.
content resume by 
$git reset --hard 97aaf29-->get by git reflog

总结创建与合并分支命令如下：

　　查看分支：git branch

　　创建分支：git branch name

　　切换分支：git checkout name

　　创建+切换分支：git checkout –b name

　　合并某分支到当前分支：git merge name

　　删除分支：git branch –d name

