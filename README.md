# Информационные технологии и программирование, ПИЖ-б-о-26-1(2), Бабаян Артём.
# Отчёт о лабораторной работе №1 по дисциплине "Информационные технологии и программирование"

### *Ход работы:*

Внимание! Этот репозиторий ([Информационные технологии и программирование, ПИЖ-б-о-26-1(2), Бабаян Артём.](https://github.com/bithoffka/inf_technologies_and_programming)) был создан для всех лабораторных работ по данной дисциплине. Репозитории, которые будут созданы в ходе работы опубликованы по другим адресам, ссылки ниже.

- Первый репозиторий: [bithoffka/first_project](https://github.com/bithoffka/first_project)
- Второй репозиторий: [bithoffka/second_project](https://github.com/bithoffka/second_project)

### *Первый репозиторий:*
![Создание первого репозитория](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/create_first_project_repo.png?raw=true)

> Краткое описание действий:

Подключился к терминалу Git Bash и ознакомился со структурой домашнего каталога с помощью команд `pwd` и `ls`. Перешёл на рабочий стол, создал папку проекта `first-project`, а затем создал в ней файлы `index.html` и `style.css`. Настроил Git, указав имя пользователя и адрес электронной почты через команды `git config`, после чего проверил сохранённые настройки. Инициализировал локальный Git-репозиторий командой `git init`, просмотрел его состояние через `git status` и убедился, что созданные файлы ещё не отслеживаются системой контроля версий. Далее добавил файлы в индекс командой `git add -A`, создал первый коммит через `git commit -m "HTML и CSS главной страницы"` и проверил историй коммитов через `git log`.

Затем создал SSH-ключ с помощью команды `ssh-keygen`, указав алгоритм шифрования и адрес электронной почты. После генерации ключа запустил SSH-агент командой `eval $(ssh-agent -s)` и добавил созданный ключ через `ssh-add`. Затем скопировал открытый ключ и добавил его в настройки аккаунта GitHub для безопасной аутентификации.

Так выглядят ключи в папке `.ssh`:

![Ключи в папке](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/keys_in_folder.png?raw=true)

Так выглядит добавление ключа в настройках репозитория:

![Добавление ключа](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/set_the_key.png?raw=true)

После этого связал локальный репозиторий с удалённым с помощью команды `git remote add origin`, выполнил отправку проекта командой `git push -u origin main` и убедился, что локальная ветка успешно связана с удалённой.

Так выглядел репозиторий до отправки:

![Репозиторий до отправки](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/thats_how_the_first_repo_looks_1.png?raw=true)

А так он выглядел после:

![Репозиторий после отправки](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/thats_how_the_first_repo_looks_2.png?raw=true)

Далее я внёс изменения в `index.html` и `style.css`:

![Изменения в HTML](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/html_changes.png?raw=true)

![Изменения в CSS](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/css_changes.png?raw=true)

Затем проверил состояние репозитория через `git status`, добавил изменения в индекс командой `git add -A`, создал новый коммит через `git commit -m "Добавлена разметка страницы"` и отправил обновлённую версию проекта на GitHub с помощью `git push`. В результате локальный репозиторий был успешно синхронизирован с удалённым репозиторием GitHub, а все изменения были сохранены в истории коммитов.

Так выглядит репозиторий сейчас:

![Репозиторий после всех изменений](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/thats_how_the_first_repo_looks_3.png?raw=true)

>Все команды в терминале:

![Скриншот терминала](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/terminal.png?raw=true)

### *Второй репозиторий:*

![Создание второго репозитория](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/create_second_project_repo.png?raw=true)

> Краткое описание действий:

Подключился к терминалу Git Bash и перешёл в каталог `dev`, затем клонировал удалённый репозиторий GitHub командой `git clone`, после чего перешёл в созданную папку проекта. Создал файлы `index.html` и `style.css` с помощью команды `touch`, добавил их в индекс командой `git add -A` и создал первый коммит через `git commit -m "Создана структура проекта"`.

После этого выполнил отправку локального репозитория на GitHub с помощью команды `git push -u origin main`. В результате структура проекта была успешно сохранена в локальном репозитории и опубликована на GitHub.

Так выглядит репозиторий после отправки:

![Репозиторий после отправки](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/thats_how_the_second_repo_looks_1.png?raw=true)

> Все команды в терминале:

![Скриншот терминала](https://github.com/bithoffka/inf_technologies_and_programming/blob/main/lab1/terminal2.png?raw=true)
