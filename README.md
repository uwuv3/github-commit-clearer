
```
git checkout --orphan TEMP_BRANCH
git add -A
git commit -am "Initial commit"
git branch -D master
git branch -m master
git push -f origin master
```
