// commands for module_17_unit_4
git switch -c 15-4-feature-1
git status
git add .
git commit -am "added file feature.txt"
git status
git add .
git commit -am "1st conflict commit"
git switch -c 15-4-feature-2
git status
git add .
git commit -am "2nd conflict commit"
git switch -c 15-4-feature-3
git add .
git commit -am "3rd conflict commit"
git push origin 15-4-feature-1
git push origin 15-4-feature-2
git push origin 15-4-feature-3
git checkout main
git branch
git merge 15-4-feature-1