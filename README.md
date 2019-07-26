# git
accumulates git basics
Git Commands
A list of my commonly used Git commands
<html>
    <body>
<h3>Getting & Creating Projects</h3>
<table>
    <thead>
        <td>Command</td><td>Description</td>
    </thead>
    <tbody>
    <tr><td>git init</td><td>Initialize a local Git repository</td></tr>
    <tr><td>git clone ssh://git@github.com/[username]/[repository-name].git</td><td>Create a local copy of a remote repository</td></tr>
    <tr><td>Basic Snapshotting</td><td></td><tr>
    <tr><td>Command</td><td>Description</td></tr>
<tr><td>git status 	Check status</td></tr>
<tr><td>git add [file-name.txt] 	Add a file to the staging area</td></tr>
<tr><td>git add -A 	Add all new and changed files to the staging area</td></tr>
<tr><td>git commit -m "[commit message]" 	Commit changes</td></tr>
<tr><td>git rm -r [file-name.txt] 	Remove a file (or folder)</td></tr>
<tr><td>Branching & Merging</td></tr>
<tr><td>Command 	Description</td></tr>
<tr><td>git branch 	List branches (the asterisk denotes the current branch)</td></tr>
<tr><td>git branch -a 	List all branches (local and remote)</td></tr>
<tr><td>git branch [branch name] 	Create a new branch</td></tr>
<tr><td>git branch -d [branch name] 	Delete a branch</td></tr>
<tr><td>git push origin --delete [branch name] 	Delete a remote branch</td></tr>
<tr><td>git checkout -b [branch name] 	Create a new branch and switch to it</td></tr>
<tr><td>git checkout -b [branch name] origin/[branch name] 	Clone a remote branch and switch to it</td></tr>
<tr><td>git checkout [branch name] 	Switch to a branch</td></tr>
<tr><td>git checkout - 	Switch to the branch last checked out</td></tr>
<tr><td>git checkout -- [file-name.txt] 	Discard changes to a file</td></tr>
<tr><td>git merge [branch name] 	Merge a branch into the active branch</td></tr>
<tr><td>git merge [source branch] [target branch] 	Merge a branch into a target branch</td></tr>
<tr><td>git stash 	Stash changes in a dirty working directory</td></tr>
<tr><td>git stash clear 	Remove all stashed entries</td></tr>
<tr><td>Sharing & Updating Projects</td></tr>
<tr><td>Command 	Description</td></tr>
<tr><td>git push origin [branch name] 	Push a branch to your remote repository</td></tr>
<tr><td>git push -u origin [branch name] 	Push changes to remote repository (and remember the branch)</td></tr>
<tr><td>git push 	Push changes to remote repository (remembered branch)</td></tr>
<tr><td>git push origin --delete [branch name] 	Delete a remote branch</td></tr>
<tr><td>git pull 	Update local repository to the newest commit</td></tr>
<tr><td>git pull origin [branch name] 	Pull changes from remote repository</td></tr>
<tr><td>git remote add origin ssh://git@github.com/[username]/[repository-name].git 	Add a remote repository</td></tr>
<tr><td>git remote set-url origin ssh://git@github.com/[username]/[repository-name].git 	Set a repository's origin branch to SSH</td></tr>
<tr><td>Inspection & Comparison</td></tr>
<tr><td>Command 	Description</td></tr>
<tr><td>git log 	View changes</td></tr>
<tr><td>git log --summary 	View changes (detailed)</td></tr>
<tr><td>git diff [source branch] [target branch] 	Preview changes before merging</td></tr>
    </tbody>
    <thead>
        </body>   </html>
