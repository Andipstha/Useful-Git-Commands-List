# Useful-Git-Commands-List
- In this article, I will talk about the Git Commands that you will be using often when you are working with Git.


| Command | Description |
| --- | --- |
| git init	|Initialize a local Git repository |
| git clone repo_url	| Clone public repository |
| git clone |ssh://git@github.com/[username]/[repository-name].git	| Clone private repository |
| git status | List all new or modified files |
| git add [file-name] | Add a file to the staging area |
| git add -A	| Add all new and changed files to the staging area |
| git commit -m "[commit message]"	| Commit changes |
| git mv [file-original] [file-renamed]"	| Rename the file and prepare it for commit |
| git rm -r [file-name.txt]	| Remove a file (or folder) |
| git rm --cached [file]	| Remove the file from version control, but preserve the file a local level |
| git branch	| List of branches (the asterisk denotes the current branch)  |
| git branch -a	| List all branches (local and remote) |
| git branch [branch name]	| Create a new branch |
| git branch -d [branch name]	| Delete a branch |
| git branch -D [branch name]	| Delete a branch forcefully |
| git push origin --delete [branch name]	| Delete a remote branch |
| git checkout -b [branch name]	| Create a new branch and switch to it |
| git checkout -b [branch name] origin/[branch name]	| Clone a remote branch and switch to it |
| git branch -m [old branch name] [new branch name]	| Rename a local branch
| git checkout [branch name]	| Switch to a branch |
| git checkout -	| Switch to the branch last checked out | 
| git checkout -- | [file-name.txt]	Discard changes to a file
| git merge [branch name]	| Merge a branch into the active branch
| git merge [source branch] [target branch]	| Merge a branch into a target branch
| git fetch [bookmark]	| Download all bookmark history from repository
| git show [commit]	| Produces metadata and content changes from the specified commit
| git stash	| Stash changes in a dirty working directory
| git stash clear	| Remove all stashed entries
| git stash pop	| Restore most recently saved files
| git stash list	| List all changesets in quick save
| git stash drop	| Remove the most recent quick save changeset
| git push origin [branch name]	| Push a branch to your remote repository
| git push -u origin [branch name]	| Push changes to remote repository (and remember the branch)
| git push	| Push changes to remote repository (remembered branch)
| git push origin --delete [branch name]	| Delete a remote branch
| git pull	| Update local repository to the newest commit
| git pull origin [branch name]	| Pull changes from remote repository
| git remote add origin ssh://git@github.com/[username]/[repository-name].git	| Add a remote repository
| git remote set-url origin ssh://git@github.com/[username]/[repository-name].git	| Set a repository's origin branch to SSH
| git log	| View changes
| git log --summary	| View changes (detailed) |
| git log --oneline	| View changes (briefly) |
| git log --follow [file]	| Lists the version history for the file, including changes by name |
| git ls-files --other --ignored --exclude-standard	| List all ignored files in this project
| git diff | Show file differences that haven't been staged |
| git diff [source branch] [target branch]	| Preview changes before merging
| git revert commitid	| Revert commit changes |
| git reset [commit]	| Undo all commits after [commit], preserving the changes locally
| git reset --hard [commit]	| Discard all history and return to the specified commit
| git config --global user.name "your_username"	| Set globally Username |
| git config --global user.email "your_email_address@example.com"	| Set globally Email id |
| git config --global --list	| Get global config |
