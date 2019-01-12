test test

Git is HARD!!!
About us page is done

CREATE A BRANCH AND MERGE CHANGES
1. Check which branch you're in:            git branch
2. If not currently in the master branch,   
   move to the master branch:               git checkout master
3. Check if there are changes to master:    git fetch
4. If there are changes, pull changes:      git pull
5. Create a new branch:                     git checkout -b <branch name>
6. Add branch to remote origin:             git push --set-upstream origin <branch name>
7. Make changes to your files and save:     cmd + s
8. Add/Commit the changes:                  git add . / git commit -m "<commit message>"
9. When you are ready to merge, move
   to master branch:                        git checkout master
10. Check to see if any changes have
    been made since you have been
    working on your branch:                 git fetch
11. If changes have been made, pull
    from remote origin:                     git pull
12. Merge branch to master:                 git merge <branch name>
13. Push to remote origin:                  git push