# Инструкция по работе с Git

## 1 часть
### 1 семинар

## Команды Git

*Git* - зто консольная утидита, для отслеживания и ведения истории изменения файлов в вашем проекте.

* *git init* - команда, инициализирующая репозиторий в заданной директориии.

* *git version* - команда, отображающая текущуюю установленную версию Git

* *git status* - команда, отображающая состояние репозитария

* *git help* - команда, открывающая руководство

* *git diff* - команда, показывающая различия веток

* *clear* - команда, очищающая рабочую область

## Создание репозитория

1. Создаем папку
2. Активируем Git: git init
3. Создаем файл с расширением .md

## *Алгоритм внесения изменений в документ*

1. Внести изменения
2. Сохранить изменения
3. Добавить отслеживание (git add)
4. Контрольная точка (git commit -m)

## 2  часть
### 1 семинар

###  Создание веток

* *git branch* - команда,отображающая все существующие ветки;

* *git branch <branch_name>* - команда, создающая новую ветку с именем branch_name;

* *git checkout <branch name>* - Команда, переходящая в другую ветку

###  Слияние веток

* *git merge <branch_name>* - команда, осуществляющая слияние текущей ветки с указанной (branch_name);

_*NB*_ Перед слиянием веток необходимо убедиться в том, что базовая и принимаемая ветка указаны верно!

###  Конфликты 

# Удаленный репозиторий