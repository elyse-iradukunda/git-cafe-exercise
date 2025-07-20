# git-cafe-exercise
## Bundle 5 
### Exercise 2
```bash
 
user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ git commit -a -m'refactor: add restorant'
[main 14a91d7] refactor: add restorant
 1 file changed, 1 insertion(+), 1 deletion(-)

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/elyse-iradukunda/git-cafe-exercise.git
   d1d3f9c..14a91d7  main -> main

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ 

```
## Bundle 6
### Exercise 2
```bash
    
user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ git branch ft/new

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ git checkout ft/new
Switched to branch 'ft/new'

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (ft/new)
$ git add menu.html 

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (ft/new)
$ git commit  -m'feat: new feature 
on my site and added page menu'    
[ft/new fd86c4f] feat: new feature on my site and added page menu     
 1 file changed, 11 insertions(+)  
 create mode 100644 menu.html      

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (ft/new)
$ git push 
fatal: The current branch ft/new has no upstream branch.
To push the current branch and set the remote as upstream, use        

    git push --set-upstream origin ft/new

To have this happen automatically for branches without a tracking     
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (ft/new)
$ git push --set-upstream origin ft
/new 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 460 bytes | 460.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas:   0% (0/1remote: Resolving deltas: 100% (1/1remote: Resolvi * [new branch]      ft/new -> ft/new
branch 'ft/new' set up to track 'origin/ft/new'.
```
### Exercise 2

```bash
 
user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (ft/new)
$ git switch main
M       README.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ git branch fix/bug

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ git switch fix/bug
M       README.md
Switched to branch 'fix/bug'       

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)
$ git commit -m'fix: bugs'
On branch fix/bug
Changes not staged for commit:     
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md      
        modified:   index-4.html   

no changes added to commit (use "git add" and/or "git commit -a")     

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)
$ git add index-4.html 

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)
$ git commit -m'fix: bugs'
[fix/bug 11c1c6c] fix: bugs
 1 file changed, 1 insertion(+), 1 deletion(-)

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)
$ git push
fatal: The current branch fix/bug has no upstream branch.
To push the current branch and set the remote as upstream, use        

    git push --set-upstream origin fix/bug

To have this happen automatically for branches without a tracking     
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)
$ git push --set-upstream 
fatal: The current branch fix/bug has no upstream branch.
To push the current branch and set the remote as upstream, use        

    git push --set-upstream origin fix/bug

To have this happen automatically for branches without a tracking     
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)
$ git push --set-upstream origin fi
x/bug 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
se-iradukunda/git-cafe-exercise/pull/new/fix/bug
remote:
To https://github.com/elyse-iradukunda/git-cafe-exercise.git
 * [new branch]      fix/bug -> fix/bug
branch 'fix/bug' set up to track 'origin/fix/bug'.

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)  
$ git checkout main
M       README.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ 

```
### Exercise 3

```bash

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)
$ git add .

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)     
$ git commit -m'last fix on bundle 6 exercise 3'
[main 4160af3] last fix on bundle 6 exercise 3
 1 file changed, 127 insertions(+)

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)     
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.42 KiB | 1.42 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/elyse-iradukunda/git-cafe-exercise.git
   c6b2dfa..4160af3  main -> main

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (main)     
$ git switch fix/bug 
Switched to branch 'fix/bug'
Your branch is up to date with 'origin/fix/bug'.

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)  
$ git commit -a -m'fix: contact numbers'
[fix/bug e0165ae] fix: contact numbers
 1 file changed, 1 insertion(+), 1 deletion(-)

user@Irael MINGW64 /d/Coding/Gym_Git_Exercise_Solutions/git-cafe-exercise (fix/bug)  
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/elyse-iradukunda/git-cafe-exercise.git
   11c1c6c..e0165ae  fix/bug -> fix/bug

```
