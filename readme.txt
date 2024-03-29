
issac@CyberKnight MINGW64 /d/git
$ cd story

issac@CyberKnight MINGW64 /d/git/story
$ touch chapter1.txt

issac@CyberKnight MINGW64 /d/git/story
$ ls
chapter1.txt

issac@CyberKnight MINGW64 /d/git/story
$ open -a /chapter1.txt
bash: open: command not found

issac@CyberKnight MINGW64 /d/git/story
$ vim chapter1.txt

issac@CyberKnight MINGW64 /d/git/story
$ gedit chapter1.txt
bash: gedit: command not found

issac@CyberKnight MINGW64 /d/git/story
$ open chapter1.txt
bash: open: command not found

issac@CyberKnight MINGW64 /d/git/story
$ git init
Initialized empty Git repository in D:/git/story/.git/

issac@CyberKnight MINGW64 /d/git/story (master)
$ ls
chapter1.txt

issac@CyberKnight MINGW64 /d/git/story (master)
$ -ls
bash: -ls: command not found

issac@CyberKnight MINGW64 /d/git/story (master)
$ -i ls
bash: -i: command not found

issac@CyberKnight MINGW64 /d/git/story (master)
$ ls -a
./  ../  .git/  chapter1.txt

issac@CyberKnight MINGW64 /d/git/story (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        chapter1.txt

nothing added to commit but untracked files present (use "git add" to track)

issac@CyberKnight MINGW64 /d/git/story (master)
$ git add .

issac@CyberKnight MINGW64 /d/git/story (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   chapter1.txt


issac@CyberKnight MINGW64 /d/git/story (master)
$ git commit -m "complete chapter1"
[master (root-commit) a4b64b2] complete chapter1
 1 file changed, 1 insertion(+)
 create mode 100644 chapter1.txt

issac@CyberKnight MINGW64 /d/git/story (master)
$ git log
commit a4b64b26b5ffe025e5b3e11512065df59f6597b2 (HEAD -> master)
Author: cyber0knight <issacnewtonmukara@gmail.com>
Date:   Fri Mar 29 11:20:00 2024 +0530

    complete chapter1