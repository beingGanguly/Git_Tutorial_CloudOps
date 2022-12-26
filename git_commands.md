git init -- Initializes an empty git repository

git status -- Have to write in a folder where we've done git init. It will give status about branch, commits and tracked-untracked files.

git branch -- Gives the info about all the branches and in which branch you are right now

git checkout -b branch_name -- To change the branch to a new branch

git checkout master -- To change the branch to the main/master branch

git add file_name -- Added for commitment(Untracked -> Staged)

git commit -m -- To commit a file with a message (Staged -> Tracked)

git restore file_name -- To restore the untracked file which is deleted

git restore --staged file_name -- To untrack a file which is already added(Staged -> Untracked)

git log -- To get the whole commit hash

git commit revert -- reverts the previous commit

git push origin main -- To publish in remote main repository of Github from local

git pull origin main -- To get the files from origin main repository of Github to local system