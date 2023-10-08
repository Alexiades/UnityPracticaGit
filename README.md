# UnityPracticaGit

## Primera Parte

PS C:\Users\aalex> cd '.\Documents\Unity_Projects\UnityPracticaGit\'
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git init
Initialized empty Git repository in C:/Users/aalex/Documents/Unity_Projects/UnityPracticaGit/.git/
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> dir


    Directory: C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        08/10/2023     18:39          11030 Mario.jpg
-a----        08/10/2023     18:41         703796 Sonic.png
-a----        08/10/2023     18:44           1274 Visita1.txt
-a----        08/10/2023     18:45            973 Visita2.txt
-a----        08/10/2023     18:47            939 Visita3.txt


PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Mario.jpg
        Sonic.png
        Visita1.txt
        Visita2.txt
        Visita3.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git add .
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Mario.jpg
        new file:   Sonic.png
        new file:   Visita1.txt
        new file:   Visita2.txt
        new file:   Visita3.txt

PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git add README.md
fatal: pathspec 'README.md' did not match any files
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> echo "# UnityPracticaGit" >> README.md
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git add README.md
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git commit -m "Primera Subida Imagenes y Txt"
[master (root-commit) ee73d6a] Primera Subida Imagenes y Txt
 6 files changed, 21 insertions(+)
 create mode 100644 Mario.jpg
 create mode 100644 README.md
 create mode 100644 Sonic.png
 create mode 100644 Visita1.txt
 create mode 100644 Visita2.txt
 create mode 100644 Visita3.txt
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git lfs track "*.png"
Tracking "*.png"
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git lfs track "*.jpg"
Tracking "*.jpg"
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git add .gitattributes
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git branch -M main
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git remote add origin https://github.com/Alexiades/UnityPracticaGit.git
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git push -u origin main
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (8/8), 698.92 KiB | 18.39 MiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Alexiades/UnityPracticaGit.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

## Segunda Parte

-Añadir una Imagene
-Añadir un txt

PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git add .
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git commit -m "Segunda Subida Imagenes y Txt"
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git branch -M main
PS C:\Users\aalex\Documents\Unity_Projects\UnityPracticaGit> git push -u origin main
Uploading LFS objects: 100% (3/3), 722 KB | 0 B/s, done.
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 1.60 KiB | 1.60 MiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Alexiades/UnityPracticaGit.git
   ee73d6a..69e7479  main -> main
branch 'main' set up to track 'origin/main'.

## Modificación README

