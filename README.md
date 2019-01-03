# git-commands

# For Checkout:
    1. git clone GIT URL -b BRANCH NAME

# For Checkin:
     1.  git pull origin BRANCH NAME
     2.  git add .
     3.  git commit -m "" 
     4.  git push origin BRANCH NAME

# In case of abort error saying overriding local changes first stash and then merge:
      1. git stash
      2. git pull origin BRANCH NAME
      3. git stash apply

Then run commands under checkin section above.

# In case of abort error because of merge conflicts while doing git stash apply in the abov section:
   
       1. Remove conflicts in the file manually.
       2. git add <Filename>
       3. git commit -m ""
       4. git push origin BRANCH NAME
