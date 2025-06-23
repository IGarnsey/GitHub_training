# GitHub Training


### First things first

* [Download Git](https://git-scm.com/downloads) if you haven't already
* git config --global user.name "YOUR NAME"
* git config --global user.email "YOUR EMAIL"

### Clone this repo to your local device

* If you didn't have the permissions to make a branch on this repo, you would need to FORK it first
* cd ..
* git clone https://github.com/IGarnsey/GitHub_training.git

### Make a new branch with your name and add your file
* git checkout -b MyBranch
* Create a file in the directory and type in the letter
* git add your-file

### Commit changes and push branch to remote
* git commit -m "Meaningful description of commit" (can also do git commit -a -m to avoid doing git add)
* git push
* Go to GitHub and submit pull request

### OR merge into main branch and commit directly to main branch in remote
* git checkout main
* git merge MyBranch
* git status
* git commit -a -m "Why"

### Where I can see issues
People editing on GitHub, and people editing locally on Git. Conflicts will stop you making a commit, and work can be lost.
