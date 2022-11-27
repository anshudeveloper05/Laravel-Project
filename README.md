 Initial setting for github
 ===========================
 step 1: git init -b main
 step 2: git add . && git commit -m "initial commit"
 step 3: $ git init -b main
 step 4: $ git init && git symbolic-ref HEAD refs/heads/main
 step 5: $ git add .
# Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.
 step 6: $ git commit -m "First commit"
# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
 step 7: $ git remote add origin <REMOTE_URL>
# Sets the new remote
 step 8: $ git remote -v
# Verifies the new remote URL
 step 9: $ git push origin main
# Pushes the changes in your local repository up to the remote repository you specified as the origin