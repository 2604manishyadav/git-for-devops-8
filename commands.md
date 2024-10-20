# Git Commands Documentation

## 1. Project Setup
- `mkdir git-for-devops`  
  Create a new directory for the project.
- `cd git-for-devops/`  
  Navigate into the project directory.
- `git init`  
  Initialize a new Git repository.

## 2. File Operations
- `vim hello_dosto.txt`  
  Edit or create the `hello_dosto.txt` file.
- `rm hello_dosto.txt`  
  Remove the `hello_dosto.txt` file.
- `touch nibba.txt`  
  Create an empty `nibba.txt` file.
- `touch nibbi.txt`  
  Create an empty `nibbi.txt` file.
- `cat nibbi.txt`  
  Display the contents of the `nibbi.txt` file.

## 3. Git Status and Add Operations
- `git status`  
  Check the status of the working directory and staging area.
- `git add nibbi.txt`  
  Stage the `nibbi.txt` file for commit.
- `git add nibba.txt`  
  Stage the `nibba.txt` file for commit.
- `git rm --cached nibba.txt`  
  Unstage the `nibba.txt` file.

## 4. Committing Changes
- `git commit -m "adding nibba and nibbi in VCS"`  
  Commit changes with a message.
- `git commit -m "added changes in nibbi"`  
  Commit changes in the `nibbi` file.
- `git commit -m "added changes of nibba about winter"`  
  Commit changes in the `nibba` file related to winter.
- `git commit -m "added nibbu"`  
  Commit changes after adding the `nibbu.txt` file.

## 5. Configuration
- `git config --global user.name "manishyadav26"`  
  Set the global Git user name.
- `git config --global user.email "hunk2604@gmail.com"`  
  Set the global Git email address.

## 6. Branching and Checkout
- `git checkout -b dev`  
  Create and switch to a new branch named `dev`.
- `git checkout master`  
  Switch to the `master` branch.
- `git branch`  
  List all branches.
- `git checkout -b from_dev`  
  Create and switch to a new branch from `dev`.

## 7. Logging and History
- `git log`  
  Display the Git commit history.
- `git log --oneline`  
  Display a summarized one-line commit history.

## 8. Other Git Operations
- `git restore nibbi.txt`  
  Restore the `nibbi.txt` file.
- `git add .`  
  Stage all changes in the working directory.

