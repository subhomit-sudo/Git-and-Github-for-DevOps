# To acces GitHub
PAT and SSH key

# Show remotes
git remote -v

# Add remote
git remote add origin <url> 

# Push branch to remote (but github not allowing password as per their release note)
git push origin <branch>

# To avoiding the Password we use PAT
git remote set-url origin https://<PAT>@github.com/subhomit-sudo/Git-and-Github-for-DevOps.git

