# LearnGit
git commands 
-------------------------

#configuration part__
git config --list__
git config --global user.name "name"__
git config --global user.email "mail"__
git config --list__

-------------------------

#SSH key generation local device to remote github__
ssh-keygen -t ed25519 -C "mail"__

#Clone a Repo__
git clone [url]__

-------------------

#working with files
git add home.html #add file to staged area
git restore --staged home.html #remove file from staged area
git status

git add -A #add all files from repo
git commit -m "message" #Commit with message
Git diff - changes made
Git log –oneline
Git show <commit id>

--------------------

#BRANCHES
git branch <branch name> #create branch__
git branch #check branch__
git checkout <branch name> #switch branch__
git checkout -b "<branch name>" #directly create and switch branch__

delete:
git branch -d <branch name>






