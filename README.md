# Logistics
#Git
Create a global .gitignore
git config --global core.excludesfile ~/.gitignore_global

Remove directory from git and local
git rm -r one-of-the-directories
git commit -m "Remove duplicated directory"
git push origin master

Git add all files modified, deleted, and untracked?
git add -A

If you want to stage file only under your current path with that working tree, then you need to use
git add -A .

Add & Commit
git add <filename>
git add *
git commit -m "Commit message"

Push The changes
git push origin master

If you have not cloned an existing repository and want to connect your repository to a remote server, you need to add it with
git remote add origin <server>

update & merge
git pull
git merge <branch>

tagging
git tag 1.0.0 1b2e1d63ff

Replace local changes. This replaces the changes in your working tree with the last content in HEAD. 
git checkout -- <filename>

If you instead want to drop all your local changes and commits, fetch the latest history from the server and point your local master branch at it like this
git fetch origin
git reset --hard origin/master

useful hints
built-in git GUI - gitk

use colorful git output
git config color.ui true

show log on just one line per commit
git config format.pretty oneline

use interactive adding
git add -i