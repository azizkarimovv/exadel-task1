gcl git@github.com:azizkarimovv/exadel-task1.git 
git add .
git commit -m "add README.md file"
git push origin master 
git checkout -b dev
git add .
git commit -m "add test_file.txt"
git push origin dev 
git checkout -b azizkarimovv-new_feature
git status 
vim .gitignore
git status 
git add .
git commit -m "add README.md file"
git push origin azizkarimovv-new_feature
git status 
git add .
git commit -m "update README.md"
git log 
git revert 1352090534179be13f20218c13ebb6c7eeb5d35a 
git log 
git checkout master 
git log > log.txt
git branch --help 
git branch -d azizkarimovv-new_feature
git checkout azizkarimovv-new_feature
git push origin --delete azizkarimovv-new_feature
git checkout master 
git add .
git commit -m "add log.txt file"
git push origin master 
git pull origin master 
git push origin master 
git checkout dev
history | tail -n 100 | grep git > git_commands.md
vim git_commands.md
