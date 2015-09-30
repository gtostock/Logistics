# Logistics
#Create a global .gitignore
git config --global core.excludesfile ~/.gitignore_global

#Remove directory from git and local
git rm -r one-of-the-directories
git commit -m "Remove duplicated directory"
git push origin master

#Git add all files modified, deleted, and untracked?
git add -A

#If you want to stage file only under your current path with that working tree, then you need to use
git add -A .

