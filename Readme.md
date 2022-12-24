# Инструкция по работе с git.

## Что такое  git?
**Git** - это наиболее популярная реализация распределённой системы контроля версий. Самая популярная реализация **git** - это[GitHub](https://github.com)

## Подготовка репозитория.
Для создания репозитория необходимо в терминале перейти в пустую папку, где в будущем будет репозиторий. Затем в терминале с папкой написать команду *git init*.

## создание коммитов.
Для создания коммита используется команда *git commit*. Для этого в терминале с папкой-репозиторием необходимо написать *git commit -m <сообщение к коммиту>*. Сообщение в коммите писать ***Обязательно!***

###  Добавление файлов к коммиту
Для добавления файла к будущему коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*. 

## перемещение между коммитами.
Для перемещения на предыдущие коммиты используется команда *git checkout*. Для этого необходимо в журнале изменений, как показано в предыдущей части, найти необходимый коммит и его номер. После чего в терминале с папкой-репозиторием написать команду *git checkout <номер коммита>*. После применения этой команды вы попадёте в состояние **Detached head**, в котором никакие изменения сохраняться не будут. Для возврата в обычное состояние необходимо написать команду *git checkout master*.
## Журнал изменений.
Для просмотра журнала изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log*. 
## Ветки в git.
Для создания отдельной ветки используется команда *git branch*. Для этого в  терминале с папкой-репозиторием необходимо написать *git branch <название ветки>*.
## Слияние веток и разрешение конфликтов.

## Удаление веток. 

## Проверка состояния файлов.
