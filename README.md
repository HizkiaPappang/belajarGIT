 Daftar tugas / branch
 1. Tugas-git
 2. Tugas-html
 3. Tugas-css
 4. Tugas-js
 5. Tugas-midProject
 6. Tugas-php
 7. Tugas-finalProject
 Daftar perintah GiT
 …

hiski@Hizkia MINGW64 ~
$ cd /d

hiski@Hizkia MINGW64 /d
$ cd tugasWEB

hiski@Hizkia MINGW64 /d/tugasWEB (master)
$ git clone https://github.com/HizkiaPappang/belajarGIT.git
fatal: destination path 'belajarGIT' already exists and is not an empty directory.

hiski@Hizkia MINGW64 /d/tugasWEB (master)
$ cd belajarGIT

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git remote -v
origin  https://github.com/HizkiaPappang/belajarGIT.git (fetch)
origin  https://github.com/HizkiaPappang/belajarGIT.git (push)

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git branch

bash: it: command not found

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git branch
* main

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ echo "Hizkia Pappang" > Tugas-git.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git.txt

nothing added to commit but untracked files present (use "git add" to track)

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the nex

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah tugas git"
[Tugas-git 5d62cdf] Menambahkan dan mengubah tugas git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git checkout

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-git
Updating 441500f..5d62cdf
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
remote: Permission to HizkiaPappang/belajarGIT.git denied to DiaMargareta.
fatal: unable to access 'https://github.com/HizkiaPappang/belajarGIT.git/': The requ

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
remote: Permission to HizkiaPappang/belajarGIT.git denied to DiaMargareta.
fatal: unable to access 'https://github.com/HizkiaPappang/belajarGIT.git/': The requ

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git config --global user.email "hiskiapappang@gmail.com"

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git config --global username "HizkiaPappang"
error: key does not contain a section: username

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git config --global username.name "HizkiaPappang"

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git config --global user.name "HizkiaPappang"

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git config user.name
HizkiaPappang

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
remote: Permission to HizkiaPappang/belajarGIT.git denied to DiaMargareta.
fatal: unable to access 'https://github.com/HizkiaPappang/belajarGIT.git/': The requ

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ ^C

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
remote: Permission to HizkiaPappang/belajarGIT.git denied to DiaMargareta.
fatal: unable to access 'https://github.com/HizkiaPappang/belajarGIT.git/': The requ

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/HizkiaPappang/belajarGIT.git
   441500f..5d62cdf  main -> main

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ echo "HTML" > Tugas-html.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the ne

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan dan mengubah Tugas-html.txt"
[Tugas-html 93516d6] Menambahkan dan mengubah Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-html
Updating 5d62cdf..93516d6
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 342 bytes | 342.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/HizkiaPappang/belajarGIT.git
   5d62cdf..93516d6  main -> main

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ echo "CSS" > Tugas-css.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan dan mengubah Tugas-css.txt"
[Tugas-css 886033e] Menambahkan dan mengubah Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-css
Updating 93516d6..886033e
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 371 bytes | 371.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/HizkiaPappang/belajarGIT.git
   93516d6..886033e  main -> main

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ echo "JS" > Tugas-js.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan dan mengubah Tugas-js.txt"
[Tugas-js 9ba75f8] Menambahkan dan mengubah Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merger Tugas-js
git: 'merger' is not a git command. See 'git --help'.

The most similar command is
        merge

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-js
Updating 886033e..9ba75f8
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/HizkiaPappang/belajarGIT.git
   886033e..9ba75f8  main -> main

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ echo "midProject" > Tugas-midProject.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git commmit -m "Menambahkan dan mengubah Tugas-midProject.txt"
git: 'commmit' is not a git command. See 'git --help'.

The most similar command is
        commit

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
A       Tugas-midProject.txt
Your branch is up to date with 'origin/main'.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-midProject
Already up to date.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Everything up-to-date

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Everything up-to-date

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git remote -v
origin  https://github.com/HizkiaPappang/belajarGIT.git (fetch)
origin  https://github.com/HizkiaPappang/belajarGIT.git (push)

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Everything up-to-date

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-midProject
Already up to date.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git commit -m "Menambahkan dan mengubah Tugas_midProject"
[main 4b9399d] Menambahkan dan mengubah Tugas_midProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-midProject
Already up to date.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 321 bytes | 321.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/HizkiaPappang/belajarGIT.git
   9ba75f8..4b9399d  main -> main

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ ^C

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ ^C

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ echo "PHP" > Tugas-php.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan dan mengubah Tugas-PHP"
[Tugas-php a2038f7] Menambahkan dan mengubah Tugas-PHP
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-php
Updating 4b9399d..a2038f7
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/HizkiaPappang/belajarGIT.git
   4b9399d..a2038f7  main -> main

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ echo "FINALPROJECT" > Tugas-finalProject.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject
fatal: pathspec 'Tugas-finalProject' did not match any files

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt


hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan dan mengubah Tugas-finalProject"
[Tugas-finalProject 6ec6991] Menambahkan dan mengubah Tugas-finalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git checktout main
git: 'checktout' is not a git command. See 'git --help'.

The most similar command is
        checkout

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-finalProject
Updating a2038f7..6ec6991
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 317 bytes | 317.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/HizkiaPappang/belajarGIT.git
   a2038f7..6ec6991  main -> main

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$
hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin -all
error: did you mean `--all` (with two dashes)?

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/HizkiaPappang/belajarGIT.git
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php

hiski@Hizkia MINGW64 /d/tugasWEB/belajarGIT (main)
$
