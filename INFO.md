git clone https://github.com/yourname/folder.git // клонирование репозитория
git diff // просмотр изменений
git add . // добавление изменений/файла
git commit // сохранение изменений
git commit -am "change1" // сохранение изменений c описанием коммита
git commit --amend // изменение описания коммита
git mv <source> <destination> // перемещение файла
git status //просмотр коммитов
git log // история всех коммитов
git reset <commit_hash> // восстановление коммита (отмена изменений)
git stash // скрыть изменения без коммита
git stash -u // скрыть изменения без коммита в неотслеживаемых файлах
git stash list // показать скрытые изменения без коммита
git stash pop // вернуть скрытые изменения без коммита
git restore <file> // восстановить файл
git checkout -- <file> // восстановить файл (старая версия git)
git branch // просмотр веток
git branch <name> // создать ветку
git checkout <name> // перейти в ветку
dir // просмотр файлов в Windows
git checkout - // переход на предыдущую используемую ветку
git checkout -b // создание ветки и переход в нее
