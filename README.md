# Git

## Table of Content

1. [Git Version Control](#git-version-control) ✅
1. History of Git ✅
1. [Git Setup](#git-setup) ✅
1. [Git init](#git-init) ✅
1. [Git commit](#git-commit) ✅
1. [Git Skipping the Staging Area](#git-skipping-the-staging-area) ✅
1. [Git Diff](#git-diff) ✅
1. [Git Remove File](#git-remove-file) ✅
1. Github Repository ✅
1. Adding Files to Remote Repository ✅
1. [Git Tag](#git-tag) ✅
1. [Git Clone a Project](#git-clone-a-project) ✅
1. [Git Branch Create](#git-branch-create) ✅
1. [Git Delete Branch](#git-delete-branch) ✅
1. [Git Branch Pushing to Remote Repository](#git-branch-pushing-to-remote-repository) ✅
1. Git Branch How it Works ✅
1. [Git Merge](#git-merge) ✅
1. [Git Rebase](#git-rebase) ✅
1. Git Merge Conflict ✅
1. [Git Time Travel](#git-time-travel) ✅
1. [Git Stash](#git-stash) ✅
1. Git Fork ✅
1. Git Pull Request ✅

## Git Version Control

* Distributed Version Control System
* Version Control
* Version Control System
* Why it is called Distributed?

1. Local Version Control System
1. Centralized Version Control System (CVCS)
1. Distributed Version Control System

## Git Setup

* `git config`
* `git config --list`
* `git config --global --list`
* `git config --global user.name "yashk024"`
* `git config --global user.email "dev.yashk24+github@gmail.com"`

## Git init

* `git init`
* `git status`
* `git init -b main`

## Git commit

* `git add .` &rarr; to move to the staging area
* `git commit -m "initial commit"`
* `git log`

## Git Skipping the Staging Area

* `git commit -a -m "3nd commit"`

## Git Diff

* `git diff` &rarr; to check for difference for the files in the working area
* `git diff --staged` &rarr; to check for difference after the file is staged

## Git Remove File

* `git rm --cached myfile.txt`

## Git Tag

* `git push origin main`
* `git remote -v`
* `git tag`
* annotated vs lightweight tag
* `git tag -a v1.0 -m "1st release"`
* `git show v1.0`
* commit and push the changes
* `git push origin v1.0`

## Git Clone a Project

* `git clone https://github.com/microsoft/vscode.git`
* `git log --pretty=oneline`

## Git Branch Create

* `git checkout -b feature1`
* `git switch -c feature2`
* `git branch`
* `git checkout main`
* `git switch main`

## Git Delete Branch

* `git branch --all`
* `git branch -d feature2`

## Git Branch Pushing to Remote Repository

* `git push origin feature1`

## Git Merge

* `git pull origin main`
* `git merge feature1`

## Git Rebase

* `git rebase feature2`

## Git Time Travel

* `git checkout 9846f5`

## Git Stash

* `git stash`
* `git stash list`
* `git stash apply`
