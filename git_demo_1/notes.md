mkdir git_demo_1
cd git_demo_1
git init
git status
echo "This is a git demo" > README.md
git status
git add README.md
git status
git commit -m "first commit"
git status

git checkout -b 'new_branch'
git status
cat README.MD
echo "This demo is fun" >> README.md
cat README.MD
git status
git add README.md
git commit -m 'second commit'
cat README.MD

git checkout master
git merge new_branch
git status
git log


 cat README.md 
 echo "Lets make another commit" >> README.md 
 git add README.md 
 git commit -m 'third commit'
 git status
 git log

git tag release_1 3132e67253f5f1d8f7a192db11af9b53e16f0a9d
git log

git checkout release_1
cat README.md
git checkout master


