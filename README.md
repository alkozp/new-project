mkdir new-project
cd new-project
git init
touch README.md
git add README.md
git commit -m "init"
git branch development
git checkout development
git add README.md
git commit -m "readme updated"
git checkout main
git merge development
git add README.md
git commit -m "readme updated after merge"