### 创建新的版本库 Repository
$ git init  
Initialized empty Git repository in F:/gitTUT/machine_learning/.git/  
$ ls -a  
./  ../  .git/  demo1.py  
$ git status  
On branch master  

No commits yet  

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        demo1.py
  
  
nothing added to commit but untracked files present (use "git add" to track)  
$ git add demo1.py  
$ git status  
On branch master  

No commits yet  

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   demo1.py  
$ git commit -m "change 1"  
[master (root-commit) 6d1a041] change 1  
 1 file changed, 0 insertions(+), 0 deletions(-)  
 create mode 100644 demo1.py  
$ git remote add origin https://github.com/YaoXT0508-lab/Machine-Learning.git  
$ git branch -M main  
$ git push -u origin main  
Enumerating objects: 6, done.  
Counting objects: 100% (6/6), done.  
Delta compression using up to 12 threads  
Compressing objects: 100% (2/2), done.  
Writing objects: 100% (6/6), 423 bytes | 211.00 KiB/s, done.  
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)  
To https://github.com/YaoXT0508-lab/Machine-Learning.git  
* [new branch]      main -> main
* branch 'main' set up to track 'origin/main'.
