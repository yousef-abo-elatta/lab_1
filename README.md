# Lab 1 - Git & GitHub Practice

## Repository
 [https://github.com/yousef-abo-elatta/lab_1]

## Branch
 master

## File
 Yousef_Mohamed_Ahmed.txt  
 Contains my full name: **Yousef Mohamed Ahmed Aboulata**



## Task Summary

 This repository demonstrates basic Git and GitHub workflow, including commits, branch management, and history manipulation.

### Steps Completed

1. **SSH Key Setup**
   - Created an SSH key and added it to GitHub for secure authentication.

2. **Repository Setup**
   - Initialized a local Git repository.
   - Created a remote repository on GitHub and linked it to the local repo.

3. **Initial Commit**
   - Created the file `Yousef_Mohamed_Ahmed.txt` with my full name.
   - Made the first commit: `my full name`.
   - Pushed the local repo to GitHub.

# Additional commits
git commit -m "commit 1"
git commit -m "commit 2"
git commit -m "commit 3"
git commit -m "commit 4"

# Delete last 2 commits
git reset --soft HEAD~2

# Add new commit
git commit -m "commit after deletion"

# Amend last commit
git commit --amend -m "finish"

# Revert last commit
git revert HEAD

---

## Git Commands Used

```bash
# SSH Key
ssh-keygen -t ed25519 -C "yousefaboulata@gmail.com"

# Local repo setup
git init
git add Yousef_Mohamed_Ahmed.txt
git commit -m "my full name"
git remote add origin git@github.com:yousef-abo-elatta/lab_1.git
git push -u origin master
