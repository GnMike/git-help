# Git-help

---


## create a new repository on the command line
```
echo "# first-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:GnMike/first-project.git
git push -u origin main
```

## push an existing repository from the command line
```
git remote add origin git@github.com:GnMike/first-project.git
git branch -M main
git push -u origin main
```
