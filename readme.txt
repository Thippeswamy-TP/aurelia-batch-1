//setting username
git config --global user.name "username"
git config --global user.name

git config --global user.email "email"
git config -- global user.email



git status //list down all modified or newly added files/folders
git branch //list down all available branches


git clone repo_url //cloning/coping repository from github

//pushing changes to the remote repository
git add . //all modified files/folders to the staging area 
git commit -m "initial commit" //files/folders which are ready to be pushed to the remote repository
git push origin BRANCH_NAME //for pushing local changes to the remote repository

//creating new branch
git branch BRANCH_NAME //create a new branch
git checkout BRANCH_NAME //gets into the specified branch

git pull origin BRANCH_NAME //pulling latest changes from remote repository to local repository

git stash //copy the changes to the clipboard
git stash apply //restore the changes to the branch

git diff //show the differences between existing vs modified changes for all files 
git diff FILE_PATH //show the differences between existing vs modified changes for mentioned file path