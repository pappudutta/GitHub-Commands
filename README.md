# GitHub-Commands

git config --global user.name "Pappu Dutta"
git config --global user.email "pappudutta279@gmail.com"
git config --global --edit

#Create & Travel Directory and File

mkdir
touch
cd
ls

#Hidden-files and folders: 
ls -a

#Create gitignore file
touch .gitignore

#Initialize Repository
git init

#Track
All : git add .
Perticular: git add <filename.extention>

git status
git log

git commit -m "<commit-name-or-describe>"

#check-branch:
git branch
git checkout <branch-name>

git merge <branch-name>

#Push to remote Github
#to check: 
git remote -v

#to add: 
git remote add origin <github-repo-url>

#add branch: 
git branch -M master

#push: 
git push -u origin master 

or
git push

---------------------------  https://learngitbranching.js.org/  ----------------------------

git checkout -b branchName :- create a branch and immediatly get active with this brach.

git merge branchName :- go to main and commit first then merge branchName

git rebase main :- command from braanch.


