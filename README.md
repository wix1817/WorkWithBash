# WorkWithBash

wix18@wix1817PC MINGW64 ~
$ cd /D/Studies/C#/TeachMeSkills/HomeWorks/

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks
$ git clone https://github.com/wix1817/WorkWithBash.git
Cloning into 'WorkWithBash'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks
$ cd WorkWithBash

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git commit -m "Created new application"
[main eb3b9d3] Created new application
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 New App.txt

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 294 bytes | 294.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/wix1817/WorkWithBash.git
   738a79b..eb3b9d3  main -> main

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git branch develop

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git checkout develop
Switched to branch 'develop'

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git commit -m "Add some new changes"
[develop 557bed5] Add some new changes
 1 file changed, 1 insertion(+)

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git push
fatal: The current branch develop has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin develop

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git push --set-upstream origin develop
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'develop' on GitHub by visiting:
remote:      https://github.com/wix1817/WorkWithBash/pull/new/develop
remote:
To https://github.com/wix1817/WorkWithBash.git
 * [new branch]      develop -> develop
branch 'develop' set up to track 'origin/develop'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git branch feature1

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git checkout feature1
Switched to branch 'feature1'

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (feature1)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (feature1)
$ git commit
[feature1 e75bf00] Add new function
 1 file changed, 3 insertions(+), 1 deletion(-)

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (feature1)
$ git push
fatal: The current branch feature1 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature1

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (feature1)
$ git push --set-upstream origin feature1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'feature1' on GitHub by visiting:
remote:      https://github.com/wix1817/WorkWithBash/pull/new/feature1
remote:
To https://github.com/wix1817/WorkWithBash.git
 * [new branch]      feature1 -> feature1
branch 'feature1' set up to track 'origin/feature1'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (feature1)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (feature1)
$ git commit -m "Add new DLL"
[feature1 ac2de29] Add new DLL
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 DLL1.txt

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (feature1)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/wix1817/WorkWithBash.git
   e75bf00..ac2de29  feature1 -> feature1

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (feature1)
$ git checkout develop
Switched to branch 'develop'
Your branch is up to date with 'origin/develop'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git merge feature1
Updating 557bed5..ac2de29
Fast-forward
 DLL1.txt    | 0
 New App.txt | 4 +++-
 2 files changed, 3 insertions(+), 1 deletion(-)
 create mode 100644 DLL1.txt

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git commit -m "Merge feature1 to develop"
On branch develop
Your branch is ahead of 'origin/develop' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/wix1817/WorkWithBash.git
   557bed5..ac2de29  develop -> develop

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git branch
* develop
  feature1
  main

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git commit -m "Add new class"
[develop fa5813f] Add new class
 1 file changed, 3 insertions(+), 1 deletion(-)

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/wix1817/WorkWithBash.git
   ac2de29..fa5813f  develop -> develop

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git branch Feature2

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git checkout Feature2
Switched to branch 'Feature2'

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (Feature2)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (Feature2)
$ git commit -m "Add DLL2"
[Feature2 3e2cbdf] Add DLL2
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 DLL2.txt

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (Feature2)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (Feature2)
$ git commit -m "Add function to work with DLL2"
[Feature2 3ed569c] Add function to work with DLL2
 1 file changed, 3 insertions(+), 1 deletion(-)

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (Feature2)
$ git push
fatal: The current branch Feature2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin Feature2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (Feature2)
$ git push --set-upstream origin Feature2
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 588 bytes | 588.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'Feature2' on GitHub by visiting:
remote:      https://github.com/wix1817/WorkWithBash/pull/new/Feature2
remote:
To https://github.com/wix1817/WorkWithBash.git
 * [new branch]      Feature2 -> Feature2
branch 'Feature2' set up to track 'origin/Feature2'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (Feature2)
$ git checkout develop
Switched to branch 'develop'
Your branch is up to date with 'origin/develop'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git rebase Feature2
Successfully rebased and updated refs/heads/develop.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git push -f
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/wix1817/WorkWithBash.git
   fa5813f..3ed569c  develop -> develop

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git commit -m "Add DLL3"
[develop 03d1e9c] Add DLL3
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 DLL3.txt

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git commit -m "Add function to work with dll3"
[develop 8f17fde] Add function to work with dll3
 1 file changed, 3 insertions(+), 1 deletion(-)

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git commit -m "Add new funny function"
[develop 605ac46] Add new funny function
 1 file changed, 3 insertions(+), 1 deletion(-)

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 12 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 811 bytes | 811.00 KiB/s, done.
Total 8 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
To https://github.com/wix1817/WorkWithBash.git
   3ed569c..605ac46  develop -> develop

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git branch
  Feature2
  develop
  feature1
* main

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git checkout develop
Switched to branch 'develop'
Your branch is up to date with 'origin/develop'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git log
commit 605ac464edcdae4d6dbe6d70c498a3098f499440 (HEAD -> develop, origin/develop)
Author: Aliaksei Pustavy <wix1817@gmail.com>
Date:   Tue Jun 6 19:22:56 2023 +0200

    Add new funny function

commit 8f17fde6e9dc50f6261ed2bf40c7573dd4546d55
Author: Aliaksei Pustavy <wix1817@gmail.com>
Date:   Tue Jun 6 19:21:47 2023 +0200

    Add function to work with dll3

commit 03d1e9c38e3c9932e70f7c26d77ef025e10ef56a
Author: Aliaksei Pustavy <wix1817@gmail.com>
Date:   Tue Jun 6 19:21:00 2023 +0200


wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (develop)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git cherry-pick 8f17fd
Auto-merging New App.txt
CONFLICT (content): Merge conflict in New App.txt
error: could not apply 8f17fde... Add function to work with dll3
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main|CHERRY-PICKING)
$ git cherry-pick --continue
error: Committing is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
U       New App.txt

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main|CHERRY-PICKING)
$ git add .

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main|CHERRY-PICKING)
$ git cherry-pick --continue
[main 2a0a669] New release with nice new functions without bugs
 Date: Tue Jun 6 19:21:47 2023 +0200
 1 file changed, 9 insertions(+)

wix18@wix1817PC MINGW64 /D/Studies/C#/TeachMeSkills/HomeWorks/WorkWithBash (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 368 bytes | 368.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/wix1817/WorkWithBash.git
   eb3b9d3..2a0a669  main -> main