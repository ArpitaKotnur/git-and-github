# why branching?
sometimes we are not sure about the commits and we deal with branching so that we can can make changes on copy and then make changes on main branch(pointer to a commit)
so basically in braching we use 
```bash
git branch BRANCH_NAME
```
to create branch
and then we merge the branch with main branch
so to view how many branches are there
we use
```bash
git branch
```
to switch the branch
```bash
git switch BRANCH_NAME
```
to merge , firtst switch to master and then merge
```bash
git merge BRANCH_NAME
```
then use esc button and write :wq to save changes

to delete the branch we use
```bash
git branch -d BRANCH_NAME
```
shortcut way 
```bash
git switch -c ui
```
it will create and also switch to that branch
# conflicts in merge
some times  same changes are done on same file by 2 differnet branches how to solve that
manually whoever is merging will get message as conflict so the user needs to manually check on the file and remove the arrows




