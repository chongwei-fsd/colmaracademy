## Setting up my Git Repo

1. Instructions to set up my local folder to point to Github
```BASH
echo "# colmaracademy" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/chongwei-fsd/colmaracademy.git
git remote -v
git push -u origin main
```