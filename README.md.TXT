
moham@DESKTOP-1SBU2AO MINGW64 ~ (master)
$ git version
git version 2.43.0.windows.1

moham@DESKTOP-1SBU2AO MINGW64 ~ (master)
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Dlib-main/
 Documents/
 Downloads/
 Favorites/
 IntelGraphicsProfiles/
 Links/
'Local Settings'@
 Microsoft/
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 PrintHood@
 PycharmProjects/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Untitled.ipynb
 Untitled1.ipynb
 Untitled2.ipynb
 Videos/
 Week1a-DataWrangling-W23.ipynb
 anaconda3/
 lab1/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 project/
'python practice'/
 scikit_learn_data/

moham@DESKTOP-1SBU2AO MINGW64 ~ (master)
$ cd project/

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ ls
Faizan_model_v1.ipynb  lab1.ipynb

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Faizan_model_v1.ipynb

nothing added to commit but untracked files present (use "git add" to track)

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git add *
warning: in the working copy of 'Faizan_model_v1.ipynb', LF will be replaced by CRLF the next time Git touches it

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git commit -m "adding faizan_model_v1"
[master 59934e0] adding faizan_model_v1
 1 file changed, 105 insertions(+)
 create mode 100644 Faizan_model_v1.ipynb

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git push origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 1.86 KiB | 635.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/mohammadfaizan116/lab1.git
 * [new branch]      master -> master

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git status
On branch master
nothing to commit, working tree clean

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git log
commit 59934e0944c602c103453af1fdf0870ecd1f858f (HEAD -> master, origin/master)
Author: Mohammad Faizan <mohammadfaizan116@gmail.com>
Date:   Tue Feb 6 14:27:26 2024 -0500

    adding faizan_model_v1

commit 40fe3af32d9c7a1f09408491dfc1a725f0c08ec8
Author: Mohammad Faizan <mohammadfaizan116@gmail.com>
Date:   Sun Jan 28 11:22:01 2024 -0500

    first commit

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git branch mohammad_v2

moham@DESKTOP-1SBU2AO MINGW64 ~/project (master)
$ git switch mohammad_v2
Switched to branch 'mohammad_v2'

moham@DESKTOP-1SBU2AO MINGW64 ~/project (mohammad_v2)
$ ls
Faizan_model_v1.ipynb  lab1.ipynb

moham@DESKTOP-1SBU2AO MINGW64 ~/project (mohammad_v2)
$ cp Faizan_model_v1.ipynb Faizan_model_v2.ipynb

moham@DESKTOP-1SBU2AO MINGW64 ~/project (mohammad_v2)
$ ls
Faizan_model_v1.ipynb  Faizan_model_v2.ipynb  lab1.ipynb

moham@DESKTOP-1SBU2AO MINGW64 ~/project (mohammad_v2)
$ git add *
warning: in the working copy of 'Faizan_model_v2.ipynb', LF will be replaced by CRLF the next time Git touches it

moham@DESKTOP-1SBU2AO MINGW64 ~/project (mohammad_v2)
$ git commit -m "adding mohammad_v2"
[mohammad_v2 2891dc5] adding mohammad_v2
 1 file changed, 105 insertions(+)
 create mode 100644 Faizan_model_v2.ipynb

moham@DESKTOP-1SBU2AO MINGW64 ~/project (mohammad_v2)
$ git status
On branch mohammad_v2
nothing to commit, working tree clean

moham@DESKTOP-1SBU2AO MINGW64 ~/project (mohammad_v2)
$ ls
Faizan_model_v1.ipynb  Faizan_model_v2.ipynb  lab1.ipynb

moham@DESKTOP-1SBU2AO MINGW64 ~/project (mohammad_v2)
$ ls
