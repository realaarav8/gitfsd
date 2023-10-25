#git operations
# calc
#all git operarions
purvs@LAPTOP-Q0API0QC MINGW64 /e/calculator-app-in-react
$ git init
Initialized empty Git repository in E:/calculator-app-in-react/.git/

purvs@LAPTOP-Q0API0QC MINGW64 /e/calculator-app-in-react (master)
$ git add .

purvs@LAPTOP-Q0API0QC MINGW64 /e/calculator-app-in-react (master)
$ git commit -m 'your message'
[master (root-commit) 6348a31] your message
 17 files changed, 27546 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 public/favicon.ico
 create mode 100644 public/index.html
 create mode 100644 public/logo192.png
 create mode 100644 public/logo512.png
 create mode 100644 public/manifest.json
 create mode 100644 public/robots.txt
 create mode 100644 src/App/App.css
 create mode 100644 src/App/App.jsx
 create mode 100644 src/App/Calculator/Calculator.jsx
 create mode 100644 src/App/operators-num-section/operators-num-section.css
 create mode 100644 src/App/operators-num-section/operators-num-section.jsx
 create mode 100644 src/index.jsx
 create mode 100644 yarn.lock

purvs@LAPTOP-Q0API0QC MINGW64 /e/calculator-app-in-react (master)
$ git remote add origin https://github.com/purrvvvv/calc.git


purvs@LAPTOP-Q0API0QC MINGW64 /e/calculator-app-in-react (master)
$ git push -u origin master
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 8 threads
Compressing objects: 100% (23/23), done.
Writing objects: 100% (24/24), 350.82 KiB | 7.80 MiB/s, done.
Total 24 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/purrvvvv/calc/pull/new/master
remote:
To https://github.com/purrvvvv/calc.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
#to merge and branch
git checkout main
git merge feature-branch
git commit
git push origin main
