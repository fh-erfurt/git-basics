# git-basics

## Level 3: Cloning and Branching

### Cloning

Q1. Clone remote repo into current dir

`$ git clone <url>`  

Q2. Clone remote repo into a subfolder

`$ git clone <url> <foldername>`  
 
### Branching 

Q5. Create a branch

`$ git branch <branchname>`

Q6. Checkout a branch

`$ git checkout <branchname>`  

Q7. Create a branch and switch a branch in same command

`$ git checkout -b <branchname>`  

Q8. Switch to master branch

`$ git checkout master`  

Q9. Merge a feature branch

`$ git merge <branchname>` 

Q10. Delete a branch

`$ git branch -d <branchname>`

Q11. Push a local branch to a upstream repo

`$ git push -u <remotename> <branchname>`
`$ git push`
`$ git push <remotename>` 

Q12. Delete a remote branch

`$ git push <remotename> --delete <branchname>` 

Q13. Show your current branch and all remote branches with their relations

`$ git branch` 
`$ git branch -av`