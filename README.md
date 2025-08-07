# GIT Commands

## Content
- [Defination](#what-is-git)
- [Prerequisites](#prerequisites)
- [Basic Setup](#basic-setup)
- [GIT Initialization](#git-initialization)
- [Checking git status](#checking-git-status)
- [Staging your files](#staging-your-files)

## What is GIT?
GIT is an **open source** distributed version control system

## Prerequisites
To use GIT, you are expected to have an updated version of the software on your operating system.
To download go to the [git website]() and download the version for your operating system

## Basic Setup
Basic GIT commands to setup initially includes:
1. To set your name
```
git config --global user.name "your name"
```
2. To set your email
```
git config --global user.email "your email"
```

## GIT Initialization
TO initialize a Git repository we use the `git init` command. To do this,
1. Navigate to your working directory
```
cd working-dir
```
2. Type the command `git init` to initialize the dir into a repository
```
git init
```

## Checking Git Status
To check the status of your git repository, you can use the command `git status` as seen below
```
git status
```

## Staging your files
Staging or adding your file is the term used to describe the process of making git track your files, this involves moving the files from the workspace to the staging area. To do this. use `git add filename` command to add a single file, `git add file 1 file 2` to add multiple files, and `git add .` or `git add -A` to add all files. Example:
```
git add index.html
``` 
```
git add index.html style.css
```
```
git add .
```

## Git log
## Git Push
## Git pull
## Git Clone
## Git Branch