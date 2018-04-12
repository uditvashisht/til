#  Revert a commit which has already been pushed to the remote.
If your local branch is checked.\
Use the following commands:
```
git reset HEAD^ --hard
git push -f origin master
```