# Welcome!

## Be default, you're working under the git 'main/master' branch. It is best recommended to create your own branch and merge changes.

## Below are some git commands for reference:


- `git clone insert repo.git`  >this will clone remote repo to your local shell  
- `git pull`  >this will ensure that you are fully syncronized with the remote branch   
- `git branch` test-branch  >this will create a new branch called 'test-branch'  
- `git add .`  >any new files / directories you created, this command will stage them so can be added  
- `git commit -a -m "add comment here"`  >any existing files you updated, your updates will now be staged  
- `git checkout test-branch`  >this will switch you from 'master' branch to the 'test-branch'  
- `git checkout master`  >once you have completed work under 'test-branch' you can switch back to the 'master' branch  
- `git merge test-branch`  >any work you completed under test-branch, those changes will now be merged to 'master' branch  
- `git status`  >this will show you your untracked changes and your present working branch  
- `git push`  >this will push all the changes you have done to the master branch  
- `git branch -d test-branch`  >this will now delete the branch you had created
