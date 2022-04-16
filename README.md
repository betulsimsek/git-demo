#### Add config for git.

```javascript
git config --global user.name betulsimsek
git config --global user.email eylulbetulsimsek@gmail.com
git config --list --global
```

### Initialize and push git

```javascript
git init

git add . // add all files to staged changes.
// or 
git add index.js // add index.js to staged changes.

git commit -m "initial commit." // add commit.

// add remote link
git remote add origin git@github.com:betulsimsek/git-demo.git

// push
git push -u origin master

// checkout 
git checkout master 
//  or 
git checkout commitID

// remove one commit from git history if not pushed.
git reset --soft HEAD~1
git reset --hard HEAD~1
```


<!-- 
push 
pull 
commit 
branch
rebase
merge 
-->