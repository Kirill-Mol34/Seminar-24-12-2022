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
Для создания отдельной ветки используется команда *git branch*. Для этого в  терминале с папкой-репозиторием необходимо написать *git branch <название ветки>*. Веток может быть огромное множество.
### Перемещение по веткам.
Для перехода из одной ветки в другую используется команда *git checkout*. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout <название ветки>*.
Для того что бы узнать в ту ли ветку мы перешли, нужно написать в терминале команду *git branch*, после чего в терминале появится список веток. Ветка в которой мы находимся будет выделена * и зеленым цветом.
## Слияние веток и разрешение конфликтов.
Для того, что бы перенести изменения из одной ветки в другую( в которой мы находимся), используется команда *git merge*. Для этого необходимо в терминале с папкой-репозиторие написать команду *git merge <название ветки>. После этого изменения из выбранной нами ветки перенесутся в ветку в которой мы находимся.
### Конфликты.
В некоторых случаях при слиянии веток возникают конфликты, для их разрешения можно воспользоваться меню быстрого разрешения конфликта, которое всплывает над изменениями в строке. Так же можно произвести разрешение конфликта в ручную, для этого мы должны произвести правки в тексте с конфликтом, а затем сохранить наши изменения с помощью выше описанных команд.


## Удаление веток. 
Что бы удалить ветку необходимо воспользоваться командой *git branch -d*. Для этого в терминале с папкой-репозиторием необходимо написать *git branch -d <название ветки>*.

## Проверка состояния файлов в терминале.
Для проверки состояния файла используют команду *git status*. Для этого необходимо в терминале с папкой-репозиторием написать команду *git status*, после чего в терминале мы увидим был ли файл изменен и отслеживается ли он в git.
