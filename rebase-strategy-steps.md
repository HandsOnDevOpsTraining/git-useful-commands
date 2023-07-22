### Get Latest Changes into your local machine
- git checkout main
- git fetch origin
- git status
- git pull origin main


### Move to your working feature branch
- git checkout <feature-branch-name>
### Rebase with latest main branch changes
- git rebase main
### May get merge conflicts
### If there are merge conflicts, then follow below process
### If there are no conflicts, then git rebase main should show a message that rebase was successful
1. Resolve conflicts manually in the VSCode UI
2. git add .
3. git rebase --continue
### After the above conflict resolution process,  then git should show a message that rebase was successful
- git push --force origin <feature-branch-name>
or
- git push -f origin <feature-branch-name>
 

