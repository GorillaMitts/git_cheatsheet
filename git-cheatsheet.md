# Git Cheat Sheet

## Git: Configurations

### Set User Name
```
$ git config --global user.name "FirstName LastName"
```
### Set User Email
```
$ git config --global user.email "your-email@email-provider.com"
```
### Turn on UI Colors

```
$ git config --global color.ui true
```
### Show current git settings
```
$ git config --list
```
## Git: starting a repository
### Initialize repository
```
$ git init
```
### Check status
```
$ git status
```
## Git: Staging Files
### Add a single file
```
$ git add <file-name>
```
### Add multiple files by name
```
$ git add <file-name><another-file-name><yet-another-file-name>
```
### Add all files in a repository
```
$ git add .
```
### Add all files in a respository using flag
```
$ git add --all
```
### Add all files in a repository using abbreviated flag
```
$ git add -A
```
### Remove cached files
```
$ git rm --cached<file-name>
```
### Reset file by name
```
$ git reset <file-name>
```
## Git: Committing to a repository
### Commit files with message
```
$ git commit -m "Message goes here"
```
### Reset commit header
```
$ git reset --soft HEAD^
```
### Amend Commit message
```
$ git commit --amend -m <enter your message>
```
## Git Pulling and Pushing from and to repsitories
### Add remote repository origin
```
$ git remote add origin <link>
```
### Push to origin
```
$ git remote push -u origin master
```
### Clone repository
```
$ git clone <link>
```
### Pull repository of remote
```
$ git pull
```
## Git: Branching
### Branch current
```
$ git branch
```
### Branch current and add branch name
```
$ git branch <branch-name>
```
### Checkout branch by name
```
$ git checkout <branch-name>
```
### Merge branch
```
$ git merge <branch-name>
```
### Checkout branch
```
$ git checkout -b <branch-name>
```