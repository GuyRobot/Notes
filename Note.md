- $@ is the name of the file to be made
- $? is the names of the changed dependents
- $< the name of the related file that caused the action
- $* the prefix shared by target and dependent files

Git rebase https://stackoverflow.com/questions/11709885/git-rebase-merge-conflict
```
git checkout -b temp
git merge origin/master
```
```
git commit -m "Merge branch 'origin/master' into 'temp'"
```
```
git checkout alpha
git rebase origin/master -X theirs
```
```
git merge --ff $(git commit-tree temp^{tree} -m "Fix after rebase" -p HEAD)
```

Curl ca-certifate
```
export CURL_CA_BUNDLE=/etc/ssl/certs/ca-certificates.crt
```

[hanhnm0111@gmail.com](mailto:hanhnm0111@gmail.com "mailto:hanhnm0111@gmail.com")
