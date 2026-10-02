# what is stashing - ( holding your current file working in temp bag)
take scenorio where you make so many changes and suddenly you want to modifiy which should not include in previous changes so do put all the working files in stash <br> and do other changes and commit it , then remove the files from stash and work on it 
stash- putting some files on hold or store
```bash
git stash
```
to see the list of stash
```bash
git stash list
```
how to get back all the files from stash
```bash
git stash pop
```
if you want chages to be in stash and also wwant it to be pop then use
```bash
git stash apply
```
