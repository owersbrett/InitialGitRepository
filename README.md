# Command Line Definitions:

## cd - change directory

## ls - list directory contents

## man <command> - displays manual for given command

## mkdir <directory/folder name> - make directory

## pwd - print working directory (Where am I?)

## touch <filename> - create file with given name

## nano <file> - opens nano editor

# Git Definitions

## git init - initialize an empty repository, required only once per repository

## git add <file name> - moves a modified file to the staging area, this happens after editting file in nano

## git commit -m "<message>" - moves staged files to the Git Directory and labels them with the commit with a message for other developers, this happens after adding file to stage

## git status -> shows status of files

## git config --global user.name "<name>" - change or set global username

## git config --global user.email "<email>" - change or set global email address

## git config --global --list - displays your global settings

## git config --global core.editor <editor of choice> - set your global editor

## git commit --amend -m "<new message>" - changes the commit message of the last commit to the new message

## git reset HEAD <filename> - moves the staged file from the staging area to the working directory

## git checkout -- <filename> - removes any changes made to the file and reverts its status back to unmodified

## git branch <branchname> - create a new branch with the given name

## git checkout <branchname> - switch to new branch

## git checkout -b <branch name> create new branch and switch to it

## git branch -d <branchname> - delete existing branch with given name

## git merge - merge the histories of divergent branches into one branch

## git rebase - apply all of the changes from one divergent branch onto another branch

# Logical flow

## Working > Staging > GitDirectory

## Untracked > tracked > unmodified > modified > staged > committed
