# Git-Commands

## Adding an existing project to GitHub using the command line

$ git init

$ git add .

$ git commit -m "First commit"

$ git remote add origin remote repository URL

$ git remote -v

$ git push origin master

--------------------------------------------------------

## Commit

**Commit changes to head (but not yet to the remote repository):**

$ git commit -m "Commit message"

**Commit any files you've added with git add, and also commit any files you've changed since then:**

git commit -a

git push origin master

## Status

git status

## Branches

**Create a new branch and switch to it:**

git checkout -b <branchname>
  
  
**Switch from one branch to another:**

git checkout <branchname>
  
  
**List all branches:**

git branch


**Delete the feature branch:**

git branch -d <branchname>

git push origin <branchname>
  
git push --all origin
