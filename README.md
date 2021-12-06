# GIT cheat sheet

## Top 30 Git commands

1. Set up your username and email
 ```
 git config --global user.name "max-p0w3r"
```
 
2. Cache your login credentials  
```
git config --global credential.helper cache
```
3. Initialize a repository  
```
git init
```
4. Add individual file or all files to staging area   ``
```
git add somefile.js
```
5. Check a repository status
```
git status
```
6. Commit changes with a single line message or through an editor
```
git commit -m "Your short message about the commit"
```
7. View commit history with changes
```
git log -p
```
8. View a particular commit
```
git show "ID or hash of the commit" 
git show "short hash to get the same result"
```
9. View changes before committing
```
git diff
```
10. Remove tracked files from the current working tree
```
git rm dirname/somefile.js
git rm dirname/*.html
```
11. Rename files
```
git mv dir1/somefile.js dir2
```
12. Revert unstaged and staged changes
```
git checkout somefile.js
```
13. Amend the most recent commit
```
git commit --amend -m "Updated message for the previous commit"
```
14. Rollback last commit
```
git revert
```
15. Rollback a particular commit
```
git revert ID
```
16. Create and switch to a new branch
```
git branch new_branch_name
git checkout -b new_branch_name
```
17. List all branches
```
git branch
git branch -a
```
18. Delete a branch
```
git branch -d existing_branch_name
git branch -D existing_branch_name
```
19. Merge two branches
```
git merge existing_branch_name
```
20. Show commit log as graph for current or all branches
```
git log --graph --oneline --decorate
git log --all --graph --oneline --decorate
```
21. Abort a conflicting merge
```
git merge --abort
```
22. Add a remote repository
```
git remote add awesomeapp https://github.com/someurl..
```
23. View remote URLs
```
git remote -v
```
24. Get additional information about a remote repository
```
git remote show origin
```
25. Push changes to a remote repository
```
git push origin main
```
26. Pull changes from a remote repository
```
git pull
git pull --verbose
```
27. Merge remote repository with local repository
```
git merge origin
```
28. Push a new branch to a remote repository
```
git push -u origin new_branch
```
29. Remove a remote branch
```
git push --delete origin existing_branch
```
30. Use rebase
```
git rebase branch_name
```


















