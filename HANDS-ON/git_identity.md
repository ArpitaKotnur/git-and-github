```bash
git config --global user.name "arpita"
git config --global user.email "app@gamil.com"
```
this commands are to acknowledge others that who changed what file like who user with what email id

---
```bash
git init
git status
```
this command is to create a repo to a file to track 
- in folder option ,click on view nd show hidden file
- you will get all the hidden file of git (.git)
```bash
git add FILE_NAME
git add FILE_NAME FILE_NAME
git add .
git commit -m "changes you did ,mention it"
```
to add one or many file from working directory to staging area
commit- will tell what changes you did so that others can get it
```bash
git log
```
head->master - head is pointing to master branch
it also gives unwanted info which i don't want rn
so we have for oneline info
```bash
git log --oneline
```
when you do changes in files and check the status you will again come back from staging area to working stage
now you again need to add file to staging area and commit repo

---
now how to bring back from staging stage to working stage
```bash
git restore --staged FILE_NAME
```
to unstaged

---
# how to ignore the files which i dont want git to be tracked 
why dont you want to share all files?
cuz some of the files are imp and secrets like env files for secret key api key
follow the steps
- in vs code in terminal downlaod git
- open the folder as git in bash
- create .gitignore file in which you will put the name of file or folder to ignore by git
- when you add all the files in git and do modification in the files you dont want to show , those folders or files will see status as gitignore modified

# git don't track on empty files
then how to make them as the part of git
in your folder which is empty create a folder named .gitkeep






