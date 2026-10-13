# GITHUB
git in cloude <br> when you want to push your code in web you use github which stores all your files 
# private repo
when you want to clone a private repo than git wont allow for privacy , it ask for ssh key which will allow to clone, create a ssh key and then use , so when you give a link to clone use ssh link
# how to push code in github
```bash
git push origin main
```
```bash
git remote -v
```
its the name of place where our repo is sitting, its default name is origin you can also change that to whatever name you want
# to change the name of branch or change the name of main branch you use
```bash
git branch -M name_of_branch_you_want
```
# my git consider the main branch as master 
i can change that using
```bash
git config --global init.defaultBranch main
```
# git and github
git uses master and github use main so you can make it main in git
# git fetch and git pull
git fetch will fetch the commits did in remote in your local working repo whereas in git pull it also the merges the commits happened in your local directory



