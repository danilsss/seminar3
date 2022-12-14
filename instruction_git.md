# **Инструкция по работе с Git**

![Логотип](images/git.jpg)


## Что такое Git

Git (произносится «гит»[7]) — распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано.

## Создание локального репозитория

Для того, чтобы создать (инициализировать) локальный репозиторий необходимо в терминале, находясь в папке проекта набрать команду: 

    git init

## Проверка состояния репозитория

Чтобы проверить состояние репозитория ипользуют команду:

    git status

## Добавление изменений в файл

Чтобы добавить изменения в файл используют команду:

    git add <filename>

## Сохранение изменений в репозиторий

Чтобы сохранить изменения используют команду

    git commit

## Комментарий для сохранения

Чтобы оставить комментарий для сохранения без вызова дополнительной консоли используют команду:

    git commit -m "message"

## Автоматическое сохранение

Для совершения сохранения, автоматически индексируя изменения в файлах
проекта используют команду:

    git commit -a

## Объединение проиндексированных изменений с предыдущим коммитом без создания нового коммита

Чтобы объединить проиндексированные изменений с предыдущим коммитом без создания нового коммита используют команду:

    git commit -am

## Просмотр истории коммитов

Для просмотра истории коммитов используют команду:

    git log

## Переключение между версиями

Для переключения на другую версию репозитория используют команду:

    git checkout <hash>

## Просмотр изменений

Для просмотра различий между версиями используют команду:

    git diff <hash1> <hash2>

## Ветвления

Ветвления нужны для отклонения от основного кода и продолжения работы независимо от него

## Создание новой ветки

Для того чтобы создать новую ветку необходимо выполнить команду:

    git branch <branchname>  

## Удаление веток

Для того чтобы удалить ветку используют команду:

    git branch -d <branchname>

## Слияние

Чтобы выполнить слияние веток необходимо воспользоваться командой:

    git merge <branchname>
    
Где branchname это имя ветки котрую мы хотим добавить в основную

## Просмотр веток

Чтобы увидеть все существующие ветки необходимо использовать команду:

    git branch

## Удаленные репозитории

Удалённые репозитории представляют собой версии вашего проекта, сохранённые в интернете или ещё где-то в сети. У вас может быть несколько удалённых репозиториев, каждый из которых может быть доступен для чтения или для чтения-записи.

### Загрузка новых изменений в удаленный репозиторий

Для того чтобы загрузить сделанные локально изменения в удаленный репозиторий нужно использовать команду:

    git push
