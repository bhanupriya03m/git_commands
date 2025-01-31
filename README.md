# Git Commands Reference

# Basic Commands

## SETUP
| **Git Command** | **Description** |
|---------------|-------------|
|`git config --global user.name “[firstname lastname]` | Sets an identifiable name for commit history |
| `git config --global user.email “[valid-email]` | set an email address that will be associated with each history marker |



| **Git Command** | **Description** |
|---------------|-------------|
| `git init` | Initialize an existing directory as a Git repository |
| `git clone <repo_url>` | Clones a remote repository to your local machine. |
| `git status` | Shows the status of changes in the working directory. |

## Working with Files

| **Git Command** | **Description** |
|---------------|-------------|
| `git add <file>` | Stages a specific file for commit. |
| `git add .` | Stages all changes in the working directory. |
| `git commit -m "message"` | Commits staged changes with a descriptive message. |
| `git log` | Displays the commit history. |
| `git restore <file>` | Restores file before staging |
| `git restore --staged <file>` | Restores file from staging area |
| `git restore --source <commit_hash> <file>` | Restores file to working directory from specific commit | 
| `git diff` | Shows changes between commits or working directory |
| `git rm <file>` | Deletes file from working directory and repository |

## Tagging Commits

| `git tag` | List all tags |
| `git tag [name]` [commit sha] | Create a tag reference named `[name]` for current commit, or add `[commit sha]` to tag a specific commit |
| `git tag -a [name]` [commit sha] | Create an annotated tag object named `[name]` for current commit, or tag a specific commit |
| `git tag -d [name]` | Remove a tag from the local repository |


## Branching and Merging

| **Git Command** | **Description** |
|---------------|-------------|
| `git branch` | Lists all branches in the repository. |
| `git branch <branch_name>` | Creates a new branch. |
| `git checkout <branch_name>` | Switches to a different branch. |
| `git merge <branch_name>` | Merges a branch into the current branch. |

## Remote Repositories

| **Git Command** | **Description** |
|---------------|-------------|
| `git pull` | Fetches and merges changes from a remote repository. |
| `git push` | Pushes local commits to a remote repository. |
| `git remote -v` | Lists remote repositories linked to the local repository. |

## Undoing Changes

| **Git Command** | **Description** |
|---------------|-------------|
| `git reset --hard <commit_hash>` | Resets the repository to a specific commit. |
| `git revert <commit_hash>` | Reverts a specific commit while keeping history. |
| `git stash` | Temporarily saves uncommitted changes. |
| `git stash pop` | Restores stashed changes. |

## Additional Commands

| **Git Command** | **Description** |
|---------------|-------------|
| `git tag <tag_name>` | Creates a tag for a specific commit. |
| `git rebase <branch_name>` | Reapplies commits on top of another branch. |
| `git config --global user.name "Your Name"` | Sets the global username for Git. |
| `git config --global user.email "your.email@example.com"` | Sets the global email for Git. |

---
This README provides a structured reference for essential Git commands.
