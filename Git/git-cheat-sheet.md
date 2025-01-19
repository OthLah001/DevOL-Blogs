# Git Basic Commands Cheat Sheet

## Definition

Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your computer. This cheat sheet features the most important and commonly used Git commands for easy reference.

## Repository Setup

- `git init`: Initialize a new Git repository
- `git clone [url]`: Clone/download a repository from a remote source

## Basic Commands

- `git status`: Show the status of your working directory
- `git add [file]`: Add file(s) to staging area
  - `git add .`: Add all modified files to staging area
- `git commit -m "[message]"`: Commit staged changes with a descriptive message
- `git push`: Upload committed changes to remote repository
- `git pull`: Download and integrate changes from remote repository

## Branching

- `git branch`: List all local branches
- `git branch [branch-name]`: Create a new branch
- `git checkout [branch-name]`: Switch to specified branch
- `git checkout -b [branch-name]`: Create and switch to new branch
- `git merge [branch-name]`: Merge specified branch into current branch

## History & Differences

- `git log`: View commit history
  - `git log --oneline`: View simplified commit history
- `git diff`: Show changes between working directory and staging area
- `git diff --staged`: Show changes between staging area and last commit

## Undo Changes

- `git restore [file]`: Discard changes in working directory
- `git reset [file]`: Unstage changes while preserving modifications
- `git reset --hard HEAD`: Discard all local changes and revert to last commit
- `git revert [commit]`: Create new commit that undoes changes from specified commit

## Remote Repository

- `git remote add origin [url]`: Add remote repository
- `git remote -v`: List remote repositories
- `git fetch`: Download changes from remote without merging
- `git push origin [branch-name]`: Push local branch to remote
- `git pull origin [branch-name]`: Pull changes from remote branch

## Configuration

- `git config --global user.name "[name]"`: Set username
- `git config --global user.email "[email]"`: Set email
- `git config --list`: List all configurations

## Tips

1. Always check status before committing (`git status`)
2. Write clear, descriptive commit messages
3. Create new branches for new features/fixes
4. Pull before pushing to avoid conflicts
5. Regularly commit changes to maintain clean history

---

## Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/othmane-lahrimi/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/_dev__ol/)
