# git-commands

# For Checkout:
git clone GIT URL -b BRANCH NAME

# For Checkin:
git pull origin BRANCH NAME
git add .
git commit -m ""
git push origin BRANCH NAME

# In case of abort error saying overriding local changes first stash and then merge:
git stash
git pull origin BRANCH NAME
git stash apply

Then run commands under checkin section above.


