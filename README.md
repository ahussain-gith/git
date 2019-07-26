# git

<html>
    <body>
       
<h2>A list of my commonly used Git commands</h2>
<h3>Getting & Creating Projects</h3>
<table>
    <thead>
        <td>Command</td><td>Description</td>
    </thead>
    <tbody>
    <tr><td>git init</td><td>Initialize a local Git repository</td></tr>
    <tr><td>git clone ssh://git@github.com/[username]/[repository-name].git</td><td>Create a local copy of a remote repository</td></tr>
    </tbody></table>
   <h3>Basic Snapshotting</h3>
   <table>
    <thead>
        <td>Command</td><td>Description</td>
    </thead>
    <tbody>
<tr><td>git status 	Check status</td></tr>
<tr><td>git add [file-name.txt]</td><td> 	Add a file to the staging area</td></tr>
<tr><td>git add -A </td><td>	Add all new and changed files to the staging area</td></tr>
<tr><td>git commit -m "[commit message]" </td><td>	Commit changes</td></tr>
<tr><td>git rm -r [file-name.txt] </td><td>	Remove a file (or folder)</td></tr>
    </tbody><table>
    <h3>Branching & Merging</h3>
 <table>
    <thead>
        <td>Command</td><td>Description</td>
    </thead>
    <tbody>
<tr><td>git branch </td><td>	List branches (the asterisk denotes the current branch)</td></tr>
<tr><td>git branch -a 	</td><td>List all branches (local and remote)</td></tr>
<tr><td>git branch [branch name] </td><td>	Create a new branch</td></tr>
<tr><td>git branch -d [branch name] </td><td>	Delete a branch</td></tr>
<tr><td>git push origin --delete [branch name] </td><td>	Delete a remote branch</td></tr>
<tr><td>git checkout -b [branch name] </td><td>	Create a new branch and switch to it</td></tr>
<tr><td>git checkout -b [branch name] origin/[branch name] </td><td>	Clone a remote branch and switch to it</td></tr>
<tr><td>git checkout [branch name] </td><td>	Switch to a branch</td></tr>
<tr><td>git checkout - 	</td><td>Switch to the branch last checked out</td></tr>
<tr><td>git checkout -- [file-name.txt] </td><td>	Discard changes to a file</td></tr>
<tr><td>git merge [branch name] </td><td>	Merge a branch into the active branch</td></tr>
<tr><td>git merge [source branch] [target branch] </td><td>	Merge a branch into a target branch</td></tr>
<tr><td>git stash 	</td><td>Stash changes in a dirty working directory</td></tr>
<tr><td>git stash clear </td><td>	Remove all stashed entries</td></tr>
     </tbody></table>
    <h3>Sharing & Updating Projects</h3>
<table>
    <thead>
        <td>Command</td><td>Description</td>
    </thead>
    <tbody>
<tr><td>git push origin [branch name] </td><td>	Push a branch to your remote repository</td></tr>
<tr><td>git push -u origin [branch name] </td><td>	Push changes to remote repository (and remember the branch)</td></tr>
<tr><td>git push 	</td><td>Push changes to remote repository (remembered branch)</td></tr>
<tr><td>git push origin --delete [branch name]</td><td> 	Delete a remote branch</td></tr>
<tr><td>git pull 	</td><td>Update local repository to the newest commit</td></tr>
<tr><td>git pull origin [branch name]</td><td> 	Pull changes from remote repository</td></tr>
<tr><td>git remote add origin ssh://git@github.com/[username]/[repository-name].git </td><td>	Add a remote repository</td></tr>
<tr><td>git remote set-url origin ssh://git@github.com/[username]/[repository-name].git </td><td>	Set a repository's origin branch to SSH</td></tr>
    </tbody></table>
    <h3>Inspection & Comparison</h3>
    <table>
    <thead>
        <td>Command</td><td>Description</td>
    </thead>
    <tbody>
<tr><td>Command </td><td>	Description</td></tr>
<tr><td>git log </td><td>	View changes</td></tr>
<tr><td>git log --summary </td><td>	View changes (detailed)</td></tr>
<tr><td>git diff [source branch] [target branch] 	</td><td>Preview changes before merging</td></tr>
    </tbody>
    <thead>
        </body>   </html>
