![clouds](clouds-sky.jpg)

steps


git init
git branch -M main

git add .

git commit -m "Initial commit"

git remote add origin git@github.com:SamaElkhatib/lab2versioncontrol.git

ssh -T git@github.com

git push -u origin main

git switch -c dev

git add HelloDEV.txt

git commit -m "Add hellodev.txt file"

git push -u origin dev

git switch main

git switch -c test

git add .

git commit -m "test file"

git push -u origin test

git switch dev

git merge test

git push origin dev

git switch main

git merge dev

git push origin main

git switch main

git branch -d dev

git branch -d test

git push origin --delete dev

git push origin --delete test

git switch -c practice

git stash -u

git switch main

git switch practice

git stash pop

git switch main

git tag v.17

git tag

git push origin v.17

git tag


git show v.17


git tag -d v.17


git push origin --delete v.17


git add README.md

git commit -m "add readmefile"

git add .

git commit -m "updated readme"


git push origin main


git status
