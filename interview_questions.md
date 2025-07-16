## ✅ Basic Level
### 1. What is Git?
Answer:
+ Git is a distributed version control system (DVCS) that tracks changes in your code, helps in collaboration, and allows you to manage project history locally and remotely.

### 2. What is GitHub?
Answer:
+ GitHub is a cloud-based hosting service for Git repositories. It provides a platform to collaborate, store, and manage your Git repositories online.

### 3. What’s the difference between Git and GitHub?
|Git	|GitHub|
|------|------|
|Local version control tool	Online |hosting service for Git repos|
|Runs on your machine|	Runs on the cloud (web)|
|Doesn't need internet	|Requires internet|

### 4. What is a repository (repo)?
Answer:
+ A repository is a storage space for your project. It can contain `files`,` folders` ,` commit history` ,` branches` , etc.

### 5. What is the difference between git add, git commit, and git push?
Command	Purpose
+ `git add`	Stages changes for commit
+ `git commit`	Saves staged changes to local repo
+ `git push`	Sends committed changes to remote (GitHub)

## ⚙️ Intermediate Level
### 6. What is a branch in Git?
Answer:
+ A branch is a separate line of development.
+ It allows you to work on new features without affecting the main branch.

### 7. How do you create and switch to a new branch?
```
git checkout -b feature-name
``
### 8. What is a pull request (PR)?
Answer:
+ A pull request is a GitHub feature where you request to merge changes from one branch `(e.g., feature)` into another `(e.g., main)`.
+ It's used for code review and collaboration.

### 9. How do you clone a repository from GitHub?
```
git clone https://github.com/username/repo.git
```
### 10. What is the use of git status?
Answer:
+ It shows the state of your working directory and staged files—what has been modified, added, or committed.

## 🔄 Advanced & Error Handling
### 11. What is the difference between git fetch and git pull?
Command	Description
+ `git fetch`	Gets remote updates, but doesn't merge
+ `git pull`	Fetches + merges changes from remote to local

### 12. What is a merge conflict and how do you resolve it?
Answer:
+ A merge conflict occurs when Git can’t auto-merge changes. You must manually edit the conflicted file, then:
```
git add filename
git commit
```
## 13. What does git stash do?
Answer:
+ Temporarily saves changes that are not ready to be committed:
```
git stash          # Save changes
git stash pop      # Reapply them later
```
## 14. How do you undo a commit?
+ Undo last commit but keep changes:
```
git reset --soft HEAD~1
```
Undo last commit and discard changes:
```
git reset --hard HEAD~1
```
### 15. What does this error mean?
```
error: failed to push some refs...
hint: Updates were rejected because the remote contains work...
```
Answer:
+ It means your local branch is behind the remote branch. Fix it by:
```
git pull origin main --rebase
git push origin main
``
## 📌 Bonus
### 16. What is .gitignore?
Answer:
+ A file that tells Git which files/folders to ignore (e.g., node_modules, *.log, target/).

### 17. What are some common Git workflows?
Answer:

+ Git Flow

+ Feature Branch Workflow

+ GitHub Flow (PR-based)

## 18. What is git rebase?
Answer:
+ It rewrites commit history by reapplying commits on top of another branch. Used to keep a cleaner history.

19. How do you view commit history?
```
git log           # Full history
git log --oneline # Short summary
``
20. How do you delete a Git branch?
```
git branch -d branch-name            # Local
git push origin --delete branch-name # Remote
```
