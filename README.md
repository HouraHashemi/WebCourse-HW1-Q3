# WebCourse-HW1-Q3
command git practice

# 🔻First Section
‍‍
```
git add FileA.txt file
git commit -m "add FileA.txt is created"
git push -u origin main
git add FileA.txt file
git commit --amend
git push -u origin main
```


# 🔻Second Section
‍‍
```

git add x.env
git commit -m "x.env is created"
git push -u origin main
git rm --cached x.env
git commit --amend-CHEAD--allow.empty
git push -u origin main
```

# 🔻Third Section
```
git branch NewBranch
git branch
git checkout NewBranch
touch FileD.txt
git add FileD.txt
git commit -m "FileD.txt created"
git add FileD.txt
git commit -m "FileD.txt is changed"
git add FileD.txt
git commit -m "FileD.txt is changed again"
git checkout main
git cherry-pick "second-commit hashID"
git push -u origin main
git rebase NewBranch
git push -u origin main
```
