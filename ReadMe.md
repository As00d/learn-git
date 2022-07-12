# Day-1

learning how to create the repository in git and how to create a file directly using github

## Commands -

git clone url ( to bring the changes from github to local)
ls -la (to see hidden files)
git add . ( to add all the untracked files)
git add filename ( to add individual file name)

if you created a code locally and want the code to be pushed in github then the commands are -
git init
\*do all the commit
git remote add origin https://github.com/As00d/squareboat.git
adding the remote repository
git push --set-upstream origin master

That's it is done!!

// To check the branch we have a command
git branch
// to create a new branch we have a command
git checkout -b branchname
// to switch between the branches
git checkout branch_name

//if you added a file by mistake git add .
git reset filename

// if you committed by mistake
git reset HEAD~1 ( 1 here means how back u want to go)

// if you want you can use git log for using the commit id
git reset commit_id

// if you dont want to see the change in code also
git reset hard commit_id
