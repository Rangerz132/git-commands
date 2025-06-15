# Git Command Cheat Sheet

## Setup & Configuration

```bash
git config --global user.name "Your Name"         # Set Git username
git config --global user.email "you@example.com"  # Set Git email
git config --list                                 # Show current configuration
```

## Repository Initialization & Status

```bash
git init       # Initialize a new Git repository
git status     # Show status of working directory and staging area
```

## Cloning & Remote Repositories

```bash
git clone <url>                 # Clone a repository
git remote -v                   # View remotes
git remote add <name> <url>     # Add a new remote
```

## Staging & Committing

```bash
git add <file>                  # Stage a specific file
git add .                       # Stage all files
git commit -m "message"         # Commit with message
git commit -am "message"        # Add and commit tracked files
```

## Pushing & Pulling

```bash
git push                        # Push to remote
git push origin <branch>        # Push specific branch
git pull                        # Pull from remote
git fetch                       # Fetch without merging
```

## Branching & Merging

```bash
git branch                      # List branches
git branch <name>               # Create a new branch
git checkout <branch>           # Switch branch
git switch <branch>             # New command to switch branches
git checkout -b <name>          # Create and switch branch
git merge <branch>              # Merge branch into current
git branch -d <branch>          # Delete branch
```

## History & Logs

```bash
git log                         # Show commit history
git log --oneline               # Compact commit log
git show <commit>               # Show a specific commit
```

## Undoing Changes

```bash
git restore <file>              # Restore file to last commit
git restore --staged <file>     # Unstage a file
git reset                       # Reset staging area
git reset --hard                # Discard all local changes
git revert <commit>             # Revert a specific commit
```

## Diffs & Comparisons

```bash
git diff                        # Show unstaged changes
git diff --staged               # Show staged changes
git diff <branch1>..<branch2>   # Compare two branches
```

## Cleanup

```bash
git clean -f                    # Remove untracked files
git gc                          # Optimize repository
```

## Tagging

```bash
git tag                         # List tags
git tag <name>                  # Create a tag
git push origin <tag>           # Push tag to remote
```
