# Git Basics

## Basic Concept

* https://www.atlassian.com/git/tutorials/setting-up-a-repository
* https://www.codeschool.com/courses/try-git

## Setting up your Github account

* Create an account with your @artoo.in email id
* https://help.github.com/articles/set-up-git/
* Create a public respository called `Onboarding` under your username.

## Developer Workflow on Github

* Branches - master vs user/feature
* Pull Request
* Issues
* Code Review
* Travis

## Committing

```
git add
```

```
git add -A
```

```
git commit -m ""
```

```
git commit -am ""
```

Push code to remote repo. Use SSH and not HTTPS - https://help.github.com/articles/generating-ssh-keys/

## Ignore or Not

* .gitignore
* .gitkeep
* Sometimes when we work, we create extra temp files. Try that: create dummy files using `touch` in a git repo. Now do `git status` and see the new files that need to be indexed. Instead of using `rm -rf`, use a git command to removing all these files.

## Remote
```
git remote -v
```

```
git remote add origin ...
```

## Handling conflicts

```
git diff
```

```
git checkout --theirs
git checkout --ours
```

```
git reset --hard
```

## Rewriting History

Create a folder `Gitflicts` in your Onboarding repository. Create two files (Artoo.md and Me.md) and make an commit. Now add a few lines to the two files and commit them. Make changes in both files in every commit. Make atleast 3 commits. Now rewrite the git history so that first all 3 commits to Artoo.md come and then Me.md.

## Tagged releases

```
git tag -a ... 
```

## Stash

```
git stash
```
```
git apply
```
