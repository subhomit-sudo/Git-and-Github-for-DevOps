# to initialize a empty directory
git init

# to check the .git is created as a hidden file
ls -a 

![alt text](image.png)

# to check git status
git status

# to add file into staged
git add filename

# to commit the file into tracked
git commit -m "commit message"

# to configure author name and email id
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# View commit history
git log                     

# Condensed log
git log --oneline           

# Show specific commit
git show <commit>           

# Branch 
![alt text](image-2.png)

# List branches
git branch

# Switch to branch
git checkout <name>

# Create a new branch and switch
git checkout -b <name>

# Branch commit image
![alt text](image-1.png)

# Merge branch into current
git merge <branch>          

