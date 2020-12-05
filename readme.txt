Создать новую ветку pr3 локально и в удалённом реопзитории с именем b2std/ft1
git remote add b2std.ft1 https://github.com/b2std/ft1.git
git branch pr3
git push -u b2std/tf1 pr3

Удалить ветку master в удалённом репозитории с именем b2std/ft1
git push b2std/ft1 --delete master

Создание ссылки b2std/ft1 на внешний репозиторий
git remote add b2std/ft1 https://github.com/b2std/ft1.git

Удаление ссылки на внешний репозиторий
git remote remove b2std/ft1

===========================================================================
Скопировать локально ветку с внешнего репозитория
git pull b2std/ft1 pr1