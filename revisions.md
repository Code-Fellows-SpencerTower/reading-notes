# Revisions and the Cloud

## Version Control
- Version control allows you to document changes made to your code
- Local version control - one database on your computer
- Centralized version control (CVS) - database stored on a single server, allows for collaboration
- Distributed version control (DVCS) - allows for copies of the repository to be stored on different clients, prevents losing the database if the CVS goes down

## Git
- DVCS
- commit = save
- creates a snapshot of file when committed
- allows repo to be stored locally
- changes are tracked
- 3 states of git files: 
    - committed - secured on local disk
    - modified - changes made but not committed
    - staged - ready to be committed

## Git configurations
- git config --global user.name "User Name"
- git config -- global user.email "address@email.com"
- git config -- global core.editor *editorname*
- check settings: git config --list

## Set up a Git Reopsitory
- git init
- git add *.c
- git add *filename*
- git commit -m "message"

## Cloning
- git clone *address*
- git clone *address* *directory* to clone into specific directory

## Local Repository Structure
- Working Directory - where files are kept
- Index - where staged files are kept
- Head - the most recent commit / current version of file you are looking at

## ACP
- **A** add file: git add *filename* or * for all files in repository
- **C** commit file: git commit -m "message"
- **P** push file: git push origin main
- commit all changes: git commit -a

## Remote Repositories
- online versions of repositories
- "origin" - name for server repository was cloned from
- "master" - name for local branch 

## Undo Changes
- git commit --amend
- unstage a file: git reset HEAD *filename*
- undo committed snapshot: git revert HEAD
- revert file to last commit state: git checkout -- *filename*
