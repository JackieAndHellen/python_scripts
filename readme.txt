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

22791@Hellen MINGW64 ~/AndroidStudioProjects/code/GITHUB_PEROJECT/gittest (maste                                                                                            r)
$ git reset --hard 97aaf29
HEAD is now at 97aaf29 readme.txt commit

22791@Hellen MINGW64 ~/AndroidStudioProjects/code/GITHUB_PEROJECT/gittest (maste                                                                                            r)
$ cat readme.txt
1. touch <file>
2. git add . or git add <file>
3.
content resume by 
$git reset --hard 97aaf29-->get by git reflog

