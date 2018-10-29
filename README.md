## Create Branch from another repo
## Clone your branch you just made from your repos
cd into directory you want to clone the repo into
git clone <url>
cd <repo name>
git status

## Create local working branch from local master branch
git branch <branch-name> (creating a local branch)
git status (will still be in master)
git checkout <branch-name>
git status (now in the branch that was just made)

## Change some stuff in a file in the branch
git status (shows what isnt in the staging area to be committed)
git add <file-name>
git status (shows file is now staged to be committed)

git commit -m "comment for your commit" (commits the file(s))
git log (lists history of commits)

**files are now committed to out local branch we created**

## Pushing from our working local branch to our repo origin
git push -u origin <branch-name> (pushed our local branch to the origin)

**on github.com: open a pull request for what we just pushed up (this is where people could comment and colab on what you pushed up)**

**merge pull request**

git checkout master
git pull (pulls any new changes for master)


Misc.
git add .   (adds all files in local repo to be committed, also will add the folders within repo respectively)
