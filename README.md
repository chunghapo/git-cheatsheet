# git-cheatsheet

## Git global setup
```
git config --global user.name "Chung Hapo"
git config --global user.email "chung@haposoft.com"
```
## Clone new Repository 
```
git clone git@github.com:chunghapo/git-cheatsheet.git
```

## Init Existing folder and add Remote Repository 
```
cd existing_folder
git init
git remote add origin git@github.com:chunghapo/git-cheatsheet.git
git add .
git commit -m "Initial commit"
git push -u origin master
```
## Add Existing Git repository
```
cd existing_repo
git remote add origin git@github.com:chunghapo/git-cheatsheet.git
git push -u origin --all
git push -u origin --tags
```
