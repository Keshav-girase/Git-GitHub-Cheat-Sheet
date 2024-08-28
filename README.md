# Git-GitHub-Cheat-Sheet
Git &amp; GitHub Cheat Sheet for Open Source Contribution

## Basic Commands
- **`git init`**: Initialize a new Git repository.
- **`git clone <repo-url>`**: Clone an existing repository from GitHub.
- **`git status`**: Check the status of your files in the working directory.
- **`git add <file>`**: Stage changes for commit.
- **`git commit -m "message"`**: Commit staged changes with a message.
- **`git push`**: Push your commits to the remote repository.
- **`git pull`**: Fetch and merge changes from the remote repository.

## Branching
- **`git branch`**: List all branches.
- **`git branch <branch-name>`**: Create a new branch.
- **`git checkout <branch-name>`**: Switch to the specified branch.
- **`git checkout -b <branch-name>`**: Create and switch to a new branch.
- **`git merge <branch-name>`**: Merge the specified branch into the current branch.
- **`git branch -d <branch-name>`**: Delete a branch locally.

## Collaboration
- **`git fetch`**: Fetch changes from the remote repository.
- **`git pull origin <branch-name>`**: Pull changes from a specific branch.
- **`git push origin <branch-name>`**: Push your branch to the remote repository.
- **`git remote -v`**: View remote URLs.
- **`git remote add origin <url>`**: Add a remote repository.
- **`git rebase <branch-name>`**: Reapply commits on top of another base branch.

## Stashing & Cleaning
- **`git stash`**: Save your changes temporarily.
- **`git stash pop`**: Reapply the stashed changes.
- **`git stash list`**: List all stashed changes.
- **`git stash drop`**: Delete a specific stash.
- **`git clean -fd`**: Remove untracked files and directories.

## Resetting & Reverting
- **`git reset <file>`**: Unstage a file.
- **`git reset --hard <commit>`**: Reset the index and working directory to a specific commit.
- **`git revert <commit>`**: Revert changes from a specific commit.

## Tagging
- **`git tag`**: List all tags.
- **`git tag <tag-name>`**: Create a new tag.
- **`git push origin <tag-name>`**: Push a specific tag to the remote repository.

## GitHub Specific
- **`gh repo fork <repo-url>`**: Fork a repository using GitHub CLI.
- **`gh repo clone <repo-url>`**: Clone a GitHub repository using GitHub CLI.
- **`gh pr create`**: Create a new pull request using GitHub CLI.
- **`gh pr list`**: List open pull requests in the repository.
- **`gh pr merge <pr-number>`**: Merge a pull request using GitHub CLI.

## Troubleshooting
- **`git log`**: View the commit history.
- **`git diff`**: Show changes between commits, branches, etc.
- **`git blame <file>`**: Show what revision and author last modified each line of a file.
- **`git reflog`**: Show a log of all reference changes.
