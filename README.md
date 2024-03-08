# belajarGIT

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
J-Lin@DESKTOP-RV31QA4 MINGW64 ~ (master)
$ git config --global user.gmail "nicole.pakiding@gmail.com"

J-Lin@DESKTOP-RV31QA4 MINGW64 ~ (master)
$ cd Documents

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents (master)
$ git clone https://github.com/nicolergn/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents (master)
$


J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents (master)
$ cd belajarGIT

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch
* main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$


J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Tambah file Tugas-git.txt"
[Tugas-git bae946e] Tambah file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ nano Tugas-git.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Edit file Tugas-git.txt"
[Tugas-git 3e7cd04] Edit file Tugas-git.txt
 1 file changed, 1 insertion(+)

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating f51090a..3e7cd04
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 576 bytes | 16.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nicolergn/belajarGIT.git
   f51090a..3e7cd04  main -> main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$



J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Tambah file Tugas-html.txt"
[Tugas-html efb4113] Tambah file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ nano Tugas-html.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Edit file Tugas-html.txt"
[Tugas-html cf91950] Edit file Tugas-html.txt
 1 file changed, 1 insertion(+)

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Merge made by the 'ort' strategy.
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 825 bytes | 412.00 KiB/s, done.
Total 8 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/nicolergn/belajarGIT.git
   3e7cd04..fed9838  main -> main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$


J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Tambah file Tugas-css.txt"
[Tugas-css be58054] Tambah file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ nano Tugas-css.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Edit file Tugas-css.txt"
[Tugas-css 8d52f02] Edit file Tugas-css.txt
 1 file changed, 1 insertion(+)

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Merge made by the 'ort' strategy.
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 843 bytes | 281.00 KiB/s, done.
Total 8 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/nicolergn/belajarGIT.git
   fed9838..7cc279d  main -> main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$


J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout js
error: pathspec 'js' did not match any file(s) known to git

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Tambah file Tugas-js.txt"
[Tugas-js c4b058b] Tambah file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ nano Tugas-js.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Edit file Tugas-js.txt"
On branch Tugas-js
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-js.txt

no changes added to commit (use "git add" and/or "git commit -a")

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Edit file Tugas-js.txt"
[Tugas-js 7c502fb] Edit file Tugas-js.txt
 1 file changed, 1 insertion(+)

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Merge made by the 'ort' strategy.
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 780 bytes | 390.00 KiB/s, done.
Total 8 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/nicolergn/belajarGIT.git
   7cc279d..e47b739  main -> main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$


J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Tambah file Tugas-midProject.txt"
[Tugas-midProject c07a011] Tambah file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ nano Tugas-midProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Edit file Tugas-midProject.txt"
[Tugas-midProject 6082d0b] Edit file Tugas-midProject.txt
 1 file changed, 1 insertion(+)

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Merge made by the 'ort' strategy.
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 826 bytes | 275.00 KiB/s, done.
Total 8 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/nicolergn/belajarGIT.git
   e47b739..e209371  main -> main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$


J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Tambah file Tugas-php.txt"
[Tugas-php 180f229] Tambah file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ nano Tugas-php.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Edit file Tugas-php.txt"
[Tugas-php dafd410] Edit file Tugas-php.txt
 1 file changed, 1 insertion(+)

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Merge made by the 'ort' strategy.
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 785 bytes | 392.00 KiB/s, done.
Total 8 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/nicolergn/belajarGIT.git
   e209371..ce56020  main -> main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$


J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Tambah file Tugas-finalProject.txt"
[Tugas-finalProject 6fbbf28] Tambah file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ nano Tugas-finalProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Edit file Tugas-finalProject.txt"
[Tugas-finalProject 2557cc3] Edit file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Merge made by the 'ort' strategy.
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 822 bytes | 411.00 KiB/s, done.
Total 8 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/nicolergn/belajarGIT.git
   ce56020..1e025c5  main -> main

J-Lin@DESKTOP-RV31QA4 MINGW64 ~/Documents/belajarGIT (main)
$


