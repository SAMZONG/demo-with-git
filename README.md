# demo-with-git

![CleanShot 2022-08-03 at 22 34 07@2x](https://user-images.githubusercontent.com/13782141/182635551-20814839-c1f1-44a0-bdfb-024f857bd113.jpg)


## step by step

- create new branch from your want to rebase branch `brnach-from-main`
- git reset all change from `brnach-from-main`
- git rebase to `main`
  - `git rebase -i main`  noop change
- git push origin branch-from-main -f
- git cherry-pick all your change from `branch-from-branch` to `branch-from-main`
- add new update to git tracking
- git commit
- git push origin `branch-from-main`

at last, now you can merge `branch-from-main` all change to `main` and without losing your changes
