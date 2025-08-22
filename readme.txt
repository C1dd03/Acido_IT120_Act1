
jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1
$ git init
Initialized empty Git repository in C:/Users/jstin/acido_it120_act1/.git/

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ touch profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ touch education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ touch background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ touch readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ touch test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ notepad profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ notepad education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ notepad background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ notepad test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git commit -m "Save files"
[main (root-commit) 2873c9f] Save files
 5 files changed, 14 insertions(+)
 create mode 100644 background.txt
 create mode 100644 education.txt
 create mode 100644 profile.txt
 create mode 100644 readme.txt
 create mode 100644 test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git status
On branch main
nothing to commit, working tree clean

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git branch acido_b1

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git branch acido_b2

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git branch acido_b3

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git branch acido_b4

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git checkout acido_b1
Switched to branch 'acido_b1'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ notepad profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git add profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git commit -m "Update Profile"
[acido_b1 5ee2992] Update Profile
 1 file changed, 9 insertions(+), 1 deletion(-)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git checkout acido_b2
Switched to branch 'acido_b2'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ notepad education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ git add education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ git commit -m "Update Education"
[acido_b2 a5b3f51] Update Education
 1 file changed, 6 insertions(+), 1 deletion(-)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ git checkout acido_b3
Switched to branch 'acido_b3'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ notepad background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git add background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git commit -m "Update Background"
[acido_b3 e3e2654] Update Background
 1 file changed, 5 insertions(+), 1 deletion(-)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git rm test.py
rm 'test.py'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git commit -m "remove"
[acido_b3 d0d651a] remove
 1 file changed, 2 deletions(-)
 delete mode 100644 test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ ls
background.txt  education.txt  profile.txt  readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git remote add acido_it120_act1 https://github.com/C1dd03/Acido_IT120_Act1.git

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git push -u origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git push -u acido_it120_act1 main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 681 bytes | 340.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/C1dd03/Acido_IT120_Act1.git
 * [new branch]      main -> main
branch 'main' set up to track 'acido_it120_act1/main'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git push -u acido_it120_act1 acido_b1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 462 bytes | 462.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'acido_b1' on GitHub by visiting:
remote:      https://github.com/C1dd03/Acido_IT120_Act1/pull/new/acido_b1
remote:
To https://github.com/C1dd03/Acido_IT120_Act1.git
 * [new branch]      acido_b1 -> acido_b1
branch 'acido_b1' set up to track 'acido_it120_act1/acido_b1'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git push -u acido_it120_act1 acido_b2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 467 bytes | 467.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'acido_b2' on GitHub by visiting:
remote:      https://github.com/C1dd03/Acido_IT120_Act1/pull/new/acido_b2
remote:
To https://github.com/C1dd03/Acido_IT120_Act1.git
 * [new branch]      acido_b2 -> acido_b2
branch 'acido_b2' set up to track 'acido_it120_act1/acido_b2'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git push -u acido_it120_act1 acido_b3
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 540 bytes | 540.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'acido_b3' on GitHub by visiting:
remote:      https://github.com/C1dd03/Acido_IT120_Act1/pull/new/acido_b3
remote:
To https://github.com/C1dd03/Acido_IT120_Act1.git
 * [new branch]      acido_b3 -> acido_b3
branch 'acido_b3' set up to track 'acido_it120_act1/acido_b3'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git checkout acido_b4
Switched to branch 'acido_b4'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ notepad readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git rm test.py
rm 'test.py'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git commit -m "Remove test file and Update readme"
[acido_b4 7a62540] Remove test file and Update readme
 2 files changed, 204 insertions(+), 2 deletions(-)
 delete mode 100644 test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git push -u acido_it120_act1
fatal: The current branch acido_b4 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream acido_it120_act1 acido_b4

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git push -u acido_it120_act1 acido_b4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.42 KiB | 1.42 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'acido_b4' on GitHub by visiting:
remote:      https://github.com/C1dd03/Acido_IT120_Act1/pull/new/acido_b4
remote:
To https://github.com/C1dd03/Acido_IT120_Act1.git
 * [new branch]      acido_b4 -> acido_b4
branch 'acido_b4' set up to track 'acido_it120_act1/acido_b4'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git checkout acido_b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git commit -m "Sync readme.txt"
On branch acido_b4
Your branch is up to date with 'acido_it120_act1/acido_b4'.

nothing to commit, working tree clean

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git push acido_it120_act1 main
Everything up-to-date

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'acido_it120_act1/main'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git checkout acido_b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git commit -m "Sync readme file"
[main c3068bb] Sync readme file
 1 file changed, 204 insertions(+)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git checkout acido_b1
Switched to branch 'acido_b1'
Your branch is up to date with 'acido_it120_act1/acido_b1'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git checkout acido_b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git commit -m "Sync readme file"
[acido_b1 c8ec679] Sync readme file
 1 file changed, 204 insertions(+)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git push acido_b1
fatal: 'acido_b1' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.41 KiB | 1.41 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/C1dd03/Acido_IT120_Act1.git
   5ee2992..c8ec679  acido_b1 -> acido_b1

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b1)
$ git switch main
Switched to branch 'main'
Your branch is ahead of 'acido_it120_act1/main' by 1 commit.
  (use "git push" to publish your local commits)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.41 KiB | 1.41 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/C1dd03/Acido_IT120_Act1.git
   2873c9f..c3068bb  main -> main

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (main)
$ git checkout acido_b2
Switched to branch 'acido_b2'
Your branch is up to date with 'acido_it120_act1/acido_b2'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ git checkout acido_b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ git commit -m "Sync readme file"
[acido_b2 bba40d0] Sync readme file
 1 file changed, 204 insertions(+)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.41 KiB | 1.41 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/C1dd03/Acido_IT120_Act1.git
   a5b3f51..bba40d0  acido_b2 -> acido_b2

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b2)
$ git switch acido_b3
Switched to branch 'acido_b3'
Your branch is up to date with 'acido_it120_act1/acido_b3'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git checkout acido_b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git commit -m "Sync readme.file"
[acido_b3 d7ae4eb] Sync readme.file
 1 file changed, 204 insertions(+)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.40 KiB | 1.40 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/C1dd03/Acido_IT120_Act1.git
   d0d651a..d7ae4eb  acido_b3 -> acido_b3

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git switch 4
fatal: invalid reference: 4

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b3)
$ git switch acido_b4
Switched to branch 'acido_b4'
Your branch is up to date with 'acido_it120_act1/acido_b4'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_act1 (acido_b4)
$ notepad readme.txt

