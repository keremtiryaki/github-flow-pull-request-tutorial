# github-flow-pull-request-tutorial
This tutorial explains how and why GitHub Flow works

Step by step tutorial
=====

### 1) Get a copy of the repository 
```by clicking fork button.```

### 2) Clone your fork in your computer
```git clone git@github.com:<your-username>/github-flow-pull-request-tutorial.git```

### 3) Add base repository as upstream repo
```git remote add upstream git@github.com:trototype/github-flow-pull-request-tutorial.git```

use ```remote -v``` command to check configurations

```
git remote -v
origin	git@github.com:<your-username>/github-flow-pull-request-tutorial.git (fetch)
origin	git@github.com:<your-username>/github-flow-pull-request-tutorial.git (push)
upstream	git@github.com:trototype/github-flow-pull-request-tutorial.git (fetch)
upstream	git@github.com:trototype/github-flow-pull-request-tutorial.git (push)
```

### 4) Create a branch.
```git checkout -b a_new_feature_name```
This command will create local copy of the master branch and switch your branch to new one.

### 5) Make your sample changes.
Add your name in [WhoWasHere.md](WhoWasHere.md) file.

### 6) Add, Commit & Push your changes to your fork.
```
git commit -m "a message for your commit"
git push origin tutorial
```