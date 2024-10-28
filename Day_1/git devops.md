# Git grom scraatch

git log --> check remote in the folder
git status --> to see what as been commited
git branch --> to see new brach
git checkout newbranch --> to switch to new branch
git chechout -b newbranch --> to create and change baranch
git push --set-upstream origin bug_fix --> when new branch is create
git branch -d branchname  --> delete branch
git pull -r --> stacks our change ontop  remote
git rebase --continue  --> after conflict resolve
git rm -r --cached filename  --> remove from remote and local
git stash --> when u want to pull or switch branch but there is blocking code  it hide and allow operation
git stash pop --> to bring back the hidden code
git reset --hard HEAD~1  --> number how many change u want to bring back
git reset --soft HEAD~1  or git reset HEAD~1 --> to correct things in code
git commit --amend --> merge the change into the previous one
git push --force --> after using git reset --hard HEAD ~1 to push the change to remote
git revert idcomit --> undoing commit to old stae
git merge branch --> to merge thing

## Git for developers

infracture as code
cicd pipe line