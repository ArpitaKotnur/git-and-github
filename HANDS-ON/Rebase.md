# what is rebase?
it a kind of cammand to avoid merge commit<br> so when you do merge , there will be always a commit name commit , if its one commit than fine , but what if there are 100s of commits just of merge so to avoid merge commit we use rebase
<br> rebase removes all merge stuff and try to bring the commits after the branch 
<br> for example if you want to rebase on differnt branch then all the changed commits after branching will merge after the branch you currently working on
<br> if its main branch than all the commits done after branching will come after main branchs commits
# Commands for that
```bash
git rebase master
```
bring all commits from master branch to the current working branch
<br> same for main branch
```bash
git rebase branch_name
```
all commits done after branching will add after the commits of main branch
```bash
git merge branch_name
```
we are doing this just to avoid merge commit <br>
# when to use merge and rebase
if you dont need any history of your commits like mostly the merged one then you can go with rebase and if you want everything intact then use merge
