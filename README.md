# Assignment #5
*Katarzyna Kuhny, 08.04.2025*

## Table of contents
- [Why is GitHub important?](#Why-is-GitHub-important?)
- [Most useful commands](#Most-useful-commands)
  - [Setup](#Setup)
  - [Repositories management](#Repositories-management)
  - [Staging&commiting changes](#Staging&commiting-changes)
  - [Syncing with a remote repository](#Syncing-with-a-remote-repository)
  - [Branching](#Branching)

## Why is GitHub important?
+ Version control
  + Tracking changes in code
  + Managing different versions of project
+ Collaborations
  + Different people can work on a project simultaneously
  + Features like branches help with that
+ Open-source
  + Everyone can use other people's projects
  + Anyone can contribute or learn from them
+ Backup
  + Work is safe in case of local machine failure

## Most useful commands

### Setup
```git config credential.username <username>```
: *set username associated with GitHub*

```git clone <url>```
: *clone a GitHub repository to a local machine*

```git innit```
: *initialize new repository in the current directory*

### Repositories management 
```git status```
: *show status of working directory*

```git log```
: *view the commit history of a current branch*

```git diff```
: *show changes between working directory and staging area*

### Staging&commiting changes
```git add <filename>```
: *select files for later commit, add . to stage all changes*

```git commit -m "<message>"```
: *commit staged changes with a message*

### Syncing with a remote repository
```git push origin main```
: *push changes to remote rep*

```git pull origin main```
: *get changes from the remote rep to local branch*

### Branching
```git branch <branch_name>```
: *create a new branch*

```git checkout <branch_name>```
: *switch to a different branch*

```git merge <branch_name>```
: *merch a branch into a current one, git log --merge in case of conflict*
