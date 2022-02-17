* This is a project to explore git's functionality
* The project provides a base to git commit, push, pull, branch, merge
* Get started by checking out the git probook here [http://git-scm.com/book/en/v2 "git cheatsheet"] 
* Other resources here [https://docs.github.com/en/get-started/quickstart/set-up-git "Set up Git"]

#install git
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git

## Basic usage

# clones a repo
git clone <repo>

# creates a new file named test
touch test

# adds test to git 
git add test

# commit message
git commit -m "Initial commit"

# pushing changes to main branch
git push origin main

# Contributing
Pull requests are welcome. Major changes are subject to further discussions on intentions

