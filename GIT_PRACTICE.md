# Git Fundamentals Practice

This document demonstrates practical Git operations performed in this repository.

## Basic Git Commands Practiced

### 1. Repository Status
- `git status` - Check the current state of the working directory
- `git status -v` - View detailed status with changes

### 2. Viewing History
- `git log` - View commit history
- `git log --oneline` - Condensed one-line per commit view
- `git log --graph --all --decorate --oneline` - Visual graph of all branches

### 3. Branch Operations
- `git branch` - List branches
- `git branch -a` - List all branches including remotes
- `git checkout -b <branch-name>` - Create and switch to a new branch
- `git checkout <branch-name>` - Switch to an existing branch

### 4. Staging and Committing
- `git add <file>` - Stage a file for commit
- `git commit -m "message"` - Commit staged changes with a message
- `git diff` - View unstaged changes
- `git diff --staged` - View staged changes

### 5. Remote Operations
- `git remote -v` - List remote repositories
- `git push` - Push commits to remote repository
- `git pull` - Fetch and merge changes from remote

## Practice Session Summary

Date: 2026-02-06

Practiced creating branches, staging files, and committing changes to understand the fundamental Git workflow.

### Commands Executed in This Session

1. Created new branch: `git checkout -b feature/practice-git-commands`
2. Created practice documentation file
3. Staged file: `git add GIT_PRACTICE.md`
4. Viewed staged changes: `git diff --staged`
5. Committed changes: `git commit -m "Add Git fundamentals practice documentation"`
6. Viewed history: `git log --oneline`

### Key Learnings

- **Working Directory**: Where files are actively edited
- **Staging Area**: Where changes are prepared for commit
- **Repository**: Where commits are permanently stored
- **Branches**: Allow parallel development without affecting main code
- **Commits**: Snapshots of your project at specific points in time
