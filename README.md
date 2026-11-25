# practice4

git clone https://github.com/TabithaStephen/rebase-experiment.git

cd rebase-experiment

git remote -v

echo "This is the original file" > app.txt
cat app.txt
git add app.txt
git commit -m "Initial commit"

git branch
git branch feature
git branch -a

git push origin main

git fetch origin
git branch -a
git log --oneline --graph --all

git rebase origin/main
git status
vi app.txt
git add app.txt
cat app.txt
git rebase --continue

git status
git log --oneline --graph
git push origin main
