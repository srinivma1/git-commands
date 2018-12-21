# git-commands

# For Checkout:
    1. git clone GIT URL -b BRANCH NAME

# For Checkin:
     1.  git pull origin BRANCH NAME
     2.  git add .
     3.  git commit -m "" 
     4.   git push origin BRANCH NAME

# In case of abort error saying overriding local changes first stash and then merge:
git stash
git pull origin BRANCH NAME
git stash apply

Then run commands under checkin section above.


