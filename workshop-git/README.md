# inspiro-git
Materials for Inspiro Innovation Summit Git session.

```bash
git clone https://github.com/yourusername/inspiro-git
cd inspiro-git
touch yourusername.md
git add yourusername.md
git status
git commit -m "Added my username file."
git status
git log
git push origin master

# undo
git status
git commit -m "Added something to the README file"
git checkout <hash> README.md

# branch
git branch -b testing
git status
git checkout master

# merge
git checkout testing
#edit the username file
git add .
git commit -m "Added my profile link to the yourusername.md file"
git checkout master
git merge testing
git push origin master
```

Edit this.
