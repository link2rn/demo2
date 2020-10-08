# Day 1

### To initialize git into the directory
git init

### To create any file
touch <filname.extension>

### To track the file or to create stage of the file
git add .

### To create a snapshot/version
git commit -m "Commit message"

### To check the status of git
git status

### To check my updates logs
git log

### To check the available branch
git branch
(* or green current branch)

### To create a new branch
git branch <new_branchName>

### To checkout into branch
git checkout -b <branch_name>

### To delete the branch
git branch -d <branch_name>

### To merge the branch
-First of all you need to be in destination branch
git merge nayaBranch

# Day 2 Update

### To add a remote repo url
git remote add origin <REPO_URL>

### Push repo into cloud
git push -u origin <BRANCH_NAME>

### Push all branch to cloud
git push --all

### Delete remote branch from command line
git push origin -d <BRANCH_NAME>

### Reset HEAD or revert
git reset --hard HEAD~step
git reset --hard <COMMIT_ID>
