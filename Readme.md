# Инструкция для работы с Git и удалёнными репозиториями
# Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
# Подготовка репозитория
Для создание репозитория необходимо выполнить команду _git init_ в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

# Создание коммитов
## Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду git add напишите *git add <имя файла>*

Просмотр состояния репозитория
---
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

# Добавление картинок
## Картинка
   ![картинки](https://miro.medium.com/max/1400/1*vlDY5078rLn0dFQWbdAKUA.png)
## Гифка
   ![гиф](https://raw.githubusercontent.com/nadehi18/battery-wallpaper-windows/master/preview/charging.gif)
## Картинка из папки
   ![картинка](1_S-_fv45WT4MgqtnPVsxtHQ.jpeg)

# Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*
# Слияние веток
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*
# Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда _git log_. Для этого достаточно выполнить команду _git log_ в папке с репозиторием
# Ветки в Git
Создание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

смотрим команду git commit -am "save all"

# Гайд по работе с удаленными репозиториями

## Создание репозитория на GitHub

Для создания репозитория на GitHub нужно создать профиль на [GitHub](https://github.com) (*Все как обычно, ничего страшного нет: __почта, пароль, ник__*)

В панели сверху рядом с иконкой профиля выбрать __+__, а затем в выпадающем списке **New repository**. Другой вариант на главной странице зеленая кнопка **New**.

Далее заполняем поля: Repository name, Description (если хотим сделать репозиторий публичным выбираем "Public"): 

Пример заполения: 

>Repository name: __Test__

>Description: __Test repository__

Далее выбираем: __Create repository__

## Основные операции при работе с репозиториями