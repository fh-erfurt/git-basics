# git-basics

## Level 2: Staging and Remotes

### Differences

Q1. Show differences for all not staged files

`$ git diff`

Q2. Show differneces for all staged files

`$ git diff --staged`

Q3. Rest an individual file to the last commit

`$ git reset HEAD <filename>`

Q4. Reset an individual file to the last change

`$ git checkout -- <filename>`

### Learn how to reset changes before push

Q5. Undo the last commit and put changes into staging area

`$ git reset --soft HEAD^`

Q6. Undo the last commit and delete all changes

`$ git reset --hard HEAD^`

Q7. Undo the last two commits

`$ git reset --hard HEAD^^`

### Modifing a commit

Q8. Add a file to the last commit with a new commit message

`$ git add <file>`  
`$ git commit --amend -m "modify and add file"`

### Sharing

Q9. View remote repositories

`$ git remote -v`

Q10. Create a repo and GitHub and add it as remote

`$ git remote add <name> <url>`
`# git remote origin https://.../repo.git`

Q11. Remove the remote repo and add it again ;-)

`$ git remote rm <name>`

Q12. Push your branch to the remote repository

`$ git push -u <name> <branch> # origin master as local branch`
`git push # use last connection`
