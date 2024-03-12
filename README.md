 Daftar tugas / branch
 1. Tugas-git
 2. Tugas-html
 3. Tugas-css
 4. Tugas-js
 5. Tugas-midProject
 6. Tugas-php
 7. Tugas-finalProject
 Daftar perintah Git
VICTUS@KALL MINGW64 ~
$ cd "D:\matkul(semester4)\pemrograman web"

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web
$ git clone https://github.com/Paskal283/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web
$ cd belajarGIT

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git 52e63c8] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git merge Tugas-git
Updating a254ce7..52e63c8
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Paskal283/belajarGIT.git
   a254ce7..52e63c8  main -> main

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html 1cfbf24] Menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git merge Tugas-html
Updating 52e63c8..1cfbf24
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 344 bytes | 344.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Paskal283/belajarGIT.git
   52e63c8..1cfbf24  main -> main

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css 1c05e63] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git merge Tugas-css
Updating 1cfbf24..1c05e63
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 370 bytes | 370.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Paskal283/belajarGIT.git
   1cfbf24..1c05e63  main -> main

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-js aaef944] Menambahkan Tugas-Js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git merge Tugas-js
Updating 1c05e63..aaef944
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 303 bytes | 303.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Paskal283/belajarGIT.git
   1c05e63..aaef944  main -> main

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-midProject)
$ touch Tugas-Midproject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-MidProject.txt"
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Midproject.txt

nothing added to commit but untracked files present (use "git add" to track)

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-midProject)
$ git add Tugas-Midproject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-Midproject.txt"
[Tugas-midProject d7db60f] Menambahkan Tugas-Midproject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Midproject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git merge Tugas-midProject
Updating aaef944..d7db60f
Fast-forward
 Tugas-Midproject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Midproject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Paskal283/belajarGIT.git
   aaef944..d7db60f  main -> main

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-php)
$ git add TUgas-Php.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
On branch Tugas-php
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Php.txt

nothing added to commit but untracked files present (use "git add" to track)

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php d83be14] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git merge Tugas-php
Updating d7db60f..d83be14
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 300 bytes | 300.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Paskal283/belajarGIT.git
   d7db60f..d83be14  main -> main

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject 82547c4] Menambahkan Tugas-FinalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-FinalProject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git merge Tugas-finalProject
Updating d83be14..82547c4
Fast-forward
 Tugas-FinalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-FinalProject.txt

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 303 bytes | 303.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Paskal283/belajarGIT.git
   d83be14..82547c4  main -> main

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$ ^C

VICTUS@KALL MINGW64 /d/matkul(semester4)/pemrograman web/belajarGIT (main)
$
