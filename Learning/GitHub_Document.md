GitHub Document



报错：

$ git push -u origin master
To git@github.com:pcrpcx/Document.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'git@github.com:pcrpcx/Document.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

解决：

$ git reset --hard origin/master
HEAD is now at ed6fcce v1

$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean

原因：

由于改动了README.txt导致报错，使用以上方法可以重置到远程库的最新版本。但本地仓库之后的数据也会丢失。