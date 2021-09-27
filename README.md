# my_first_steps

## Questão 1

https://github.com/maumelopes/my_first_steps

## Questão 2

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git commit -m "primeiro commit"
[main (root-commit) 17db062] primeiro commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git remote add origin https://github.com/maumelopes/my_first_steps.git

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 229 bytes | 45.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/maumelopes/my_first_steps.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

## Questão 3

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git add ola_mundo.txt

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git commit -m "Adicionando o arquivo ola_mundo"
[main d9dadd9] Adicionando o arquivo ola_mundo
 1 file changed, 1 insertion(+)
 create mode 100644 ola_mundo.txt

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 152.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/maumelopes/my_first_steps.git
   17db062..d9dadd9  main -> main

## Questão 4

serei_ignorado.txt

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ touch .gitignore

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git add .

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git commit -m "Adicionando o arquivo .gitignore"
[main f3b9350] Adicionando o arquivo .gitignore
 1 file changed, 1 insertion(+)
 create mode 100644 .gitignore

Usuario@DESKTOP-18S5296 MINGW64 ~/Documents/Prog - Dev/git/my_first_steps (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/maumelopes/my_first_steps.git
   d9dadd9..f3b9350  main -> main