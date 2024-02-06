## Basic command of Git

1. Initialize a new repository: `git init`
2. Clone a repository: `git clone https://github.com/iamarbabkhan/git.git`
* Note: "iamarbabkhan" is username & "Git-Practise" is repository name
3. Configure username: `git config --global user.name "iamarbabkhan"`
* Note: "iamarbabkhan" is username
4. configure email: `git config --global user.email "arbabkhan579@gmail.com"`
* Note: "arbabkhan579@gmail.com" is email
5. git status: `git status`
6. Add a file to the staging area: `git add filename` 
7. Add all new and changed files to the staging area: `git add -A`
8. Commit changes: `git commit -m "commit message"`
9. Remove a file or folder: `git rm -r filename`
10. view log: `git log` or `git log --oneline`
11. view changes: `git diff`
12. add a remote repository: `git remote add origin https://github.com/iamarbabkhan/git.git`
* Note: "iamarbabkhan" is username & "Git-Practise" is repository name
13. add a repository using ssh: `git remote set-url origin ssh://git@github.com/iamarbabkhan/git.git`
* Note: "iamarbabkhan" is username & "Git-Practise" is repository name
14. Push a branch to remote repository: `git push origin branchname`
15. Push changes to remote repository: `git push` or `git push -u origin branchname`
16. Delete a remote branch:  `git push origin --delete branchname`
17. Pull changes from remote repository to local: `git pull` or  `git pull origin branchname`
18. find file location: `which filename` or `whereis filename`

## Git Branching

1. List branches: `git branch` 
2. List all local and remote branches:  `git branch -a`
3. Create a new branch: `git branch branchname`
4. Delete a branch: `git branch -d branchname` 
5. Delete a remote branch: `git push origin --delete branchname` 
6. Create a new branch and switch to it: `git checkout -b branchname`
7. Clone a remote branch and switch to it: `git checkout -b branchname origin/branchname`
8. Rename a local branch: `git branch -m oldbranchname newbranchname`
9. Switch to a branch: `git checkout branchname` 
10. Switch to the branch last checked out: `git checkout -`
11. Discard changes to a file: `git checkout -- filename`

## Git Merge
   
1. Merge a branch into the active branch: `git merge branchname`
2. Merge a branch into a target branch: `git merge source branch target branch`

## Git Stash

1. Stash changes in a dirty working directory: `git stash`
2. Stash File list: `git stash list`
3. Bring back to working space: `git stash apply stash@{0}`
* Note: 0 or 1 or 2 as per stash list
4. Remove all stashed entries: `git stash clear`

## Git Rebase

1. git rebase: `git rebase -i branchname`


## Git Reset
1. `git reset .`
* Note: if i add a file to staging area and i want to get back it to working space
2. `git reset --hard`
* Note: it will delete the file both from working space and staging area

## Git Revert
1. `git revert commithash`
* Note: it will undoes the changes from previous commit

## Git Clean
1. Dry run 'git clean -n'
2. Force delete `git clean -f`
* Note: this command will delete all untracked file from working space

## Git Tag
1. Add tag using commit id: `git tag -a tagname -m "message" commitid`
2. List of tag `git tag`
3. Show commit and details using tag: `git show` or `git show tagname`
4. Delete tag: `git tag -d tagname'

## Git Cherry Pick
