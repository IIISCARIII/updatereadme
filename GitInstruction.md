# Инструкция по работе с git

Создание репозитория:
```sh
git init
```

Добавить к индексации:
```sh
git add
```

Зафиксировать изменения:
```sh
git commit -m "Message text"
```

Посмотреть журнал в полном виде:
```sh
git log
```

Посмотреть журнал в сокращённом виде:
```sh
git log --oneline
```

Перемещение по веткам:
```sh
git checkout <имя_ветки>
```

Отображение всех веток:
```sh
git branch
```

Создание новой ветки:
```sh
git branch <имя_ветки>
```

Задать имя пользователя:
```sh
git config --global user.name "Name Surname"
```

Задать адрес электронной почты:
```sh
git config --global user.email "users@mail.com"
```

Проверка статуса репозитория:
```sh
git status
```

Просмотр заданного коммита:
```sh
git show <1ae17f>
```

Просмотр изменений коммита:
```sh
git diff
```

Удаление ветки:
```sh
git branch -d <branch_name>
```

Слияние двух веток:
```sh
git merge <existing_branch_name>
```

Отправка изменений в удалённый репозиторий:
```sh
git push
```

Выкачать данные с удалённого репозитория:
```sh
git pull
```

Сделать локальную копию удалённого репозитория:
```sh
git clone
```