# Git Commands Cheat Sheet

## Checking Status
git status
Checks the status of the current branch and working directory.

## Adding Changes
git add .
Stages all changes in the working directory for the next commit.

## Committing Changes
git commit -m "Message"
Commits staged changes with a descriptive message.

## Pushing Changes
git push origin main
Pushes committed changes from the local main branch to the remote repository's main branch.

git push
Shortened form of `git push origin main`, assuming the current branch is set to main.

## Rebasing Changes
git rebase
Reapplies commits on top of another base tip, usually to maintain a linear project history.

## Viewing Branches
git branch -a
Lists all local and remote branches.

## Switching Branches
git checkout <branch name>
Switches to the specified branch.

## Creating Branches
git branch <branch name>
Creates a new branch with the specified name.

## Merging Changes
git merge <branch name>
Merges the specified branch into the current branch.

## Removing Files
git rm <file name>
Removes a file from both the working directory and the index.

## Renaming Files
git mv <old file name> <new file name>
Renames a file in the working directory and stages the change.

## Viewing Commit History
git log
Displays commit history, showing commits on the current branch.

## Configuring Git
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Sets up user name and email for Git commits, globally.

## Initializing a Repository
git init
Creates a new Git repository in the current directory.

## Cloning a Repository
git clone <repository URL>
Clones a remote repository into a new directory.

## Fetching Changes
git fetch
Downloads objects and refs from another repository, typically remote ones.