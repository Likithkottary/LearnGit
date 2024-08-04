# LearnGit
git commands 
-------------------------

#configuration part\
git config --list\
git config --global user.name "name"\
git config --global user.email "mail"\
git config --list\

-------------------------

#SSH key generation local device to remote github\
ssh-keygen -t ed25519 -C "mail"\

#Clone a Repo\
git clone [url]\

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
git branch <branch name> #create branch\
git branch #check branch\
git checkout <branch name> #switch branch\
git checkout -b "<branch name>" #directly create and switch branch\

delete:
git branch -d <branch name>






