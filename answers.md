1)
git version 2.30.0.windows.2

2)
"diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt   
core.autocrlf=true
core.fscache=true
core.symlinks=false
:...skipping...
diff.astextplain.textconv=astextplain    
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt   
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
core.editor="C:\Users\julia\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
user.name=Chetnikk
user.email=julianstevovic@yahoo.com
(END)

3)
git-add(1) Manual Page Opens on a selected browser, offering Name, Synopsis, Description, Options, etc

4)
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)      
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to 
track)

5)
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)      
        answers.md

6)
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

7)
On branch master
nothing to commit, working tree clean

8)
On branch master
nothing to commit, working tree clean
PS C:\Users\julia\Desktop\cs2400\cs2400Labs\git-lab> git log
commit 3c0d0133e77a3f4d9a1def9c5d05de5cee8efe56 (HEAD -> master)
Author: Chetnikk <julianstevovic@yahoo.com>
Date:   Tue Jan 26 18:28:46 2021 -0500

9)
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

10)
No, the local file has not updated

11)
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Chetnikk/git-lab.git'
hint: Updates were rejected because the remote contains work that you 
do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12)
Yes, the local file now matches the file on github.

