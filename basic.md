mdkir tenfolder | create folder
New-Item tenfile.txt -ItemType File | create file
start . || ii . | open a folder


git reset 
git reset --hard

git rm --force | completely deletes the file

git rm --cached | only remove it from staging
git rm  -r <Folder> | all folder inside will be removed >< only folder remove

git log | view commit history


git branch | show the number of branch
git brannch <Name> | create a new branch
git checkout <Name> | switch to the branch

git log --oneline | ID of commit
git checkout <ID> | view the previous version

git diff <ID1> <ID2> | compare 2 commit
Q | exit the compare view

git push orgin <Name branch>
git fetch
git pull

git merge <branch Name> -m

git restore <file name>
git restore --staged
git restore . | restore previous version

git stash | temporarily set aside your unfinished work, switch to another branch to do sth

phase 1 working directory
git init  | create a reposity
git status | change in reposity  


phase 2 staging

git add -A || git add --all | stage every single change across the entire project
git add . | within the current directory you're in

phase 3 commit

git commit -m " message" | commit
git rm                   | delete one file




namlyf
git clone git@github.com:username-canhan/ten-du-an.git

nguyenthanhnam05work-tech
git clone git@github-work:username-congviec/ten-du-an.git