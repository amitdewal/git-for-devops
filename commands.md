
# Git Commands

## Checking the Status

1. `git status` - Shows the working tree status, indicating changes in files, staged files, and untracked files.

## Committing Changes

1. `git commit -m "Added web page"` - Commits staged changes with the message "Added web page".
2. `git commit -a -m "added about company page"` - Commits all changes in tracked files directly with the message "added about company page".

## Pushing Changes

1. `git push origin master` - Pushes the committed changes to the `master` branch of the remote repository.

## Adding and Staging Files

1. `git add about_company.html` - Stages the `about_company.html` file to be committed.
2. `git add .` - Stages all changed files for the next commit.

## Viewing Changes

1. `git diff --staged` - Shows the differences between staged changes and the last commit.
2. `git log --oneline` - Displays the commit history in a compact format with one line per commit.
3. `git log --stat` - Displays the commit logs along with file change statistics.
4. `git log --patch` - Shows the detailed patch differences introduced by each commit.

## Removing Files

1. `git rm info.txt` - Removes the file `info.txt` and stages its deletion for commit.
2. `git rm --cached README.ma` - Removes `README.ma` from the staging area but keeps it in the working directory.

## Branching and Merging

1. `git checkout -b new_branch` - Creates a new branch called `new_branch` and switches to it.
2. `git branch -a` - Lists all branches, both local and remote.
3. `git merge new_branch` - Merges the `new_branch` into the currently checked-out branch.

## Stashing Changes

1. `git stash` - Temporarily stores modified and staged changes for later reuse.
2. `git stash list` - Lists all saved stash entries.
3. `git stash show` - Shows the details of a specific stash entry.

## Configuration

1. `git config --global user.name` - Sets the global Git configuration for the user name.
2. `git config --global user.email` - Sets the global Git configuration for the user email.

## Cloning Repositories

1. `git clone <repo_url>` - Clones the remote Git repository located at `<repo_url>` to the local machine.

## Renaming and Moving Files

1. `git mv <old_file> <new_file>` - Renames or moves a file in the working directory and stages the change.

## Viewing History

1. `git log --oneline` - Displays the commit history in one line per commit format.
2. `git history` - Lists the shell command history, including the Git commands used.
