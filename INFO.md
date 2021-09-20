// commands for module_17_unit_4
git switch -c 15-4-feature-1 // создание ветки 15-4-feature-1
git status // проверка статуса
git add . // добавление файлов для отслеживания git
git commit -am "added file feature.txt" // сохранение изменений после создания файла
git status
git add .
git commit -am "1st conflict commit" // добавление 1 коммита
git switch -c 15-4-feature-2 
git status
git add .
git commit -am "2nd conflict commit"
git switch -c 15-4-feature-3
git add .
git commit -am "3rd conflict commit"
git push origin 15-4-feature-1 // сохранение изменений в git
git push origin 15-4-feature-2
git push origin 15-4-feature-3
git checkout main // переход в main
git branch
git merge 15-4-feature-1 // добавление в main измений другой ветки
git merge 15-4-feature-2
git merge 15-4-feature-3
git log
git add .
git commit -am "Added commands for 17.4"
git push origin main
