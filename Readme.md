
# инструкция по работе с git и GitHub





новая ветка создается с помощью команды *git branch < название ветки >



гит это одна из реализаций распределенных систем контроля версий,позволяющая управлять изменениями. 
## Подготовка репозитория 

Репозитойри это хранилище файлов поддерживающее версионность.создать репозиторий можно с помощью примененения команды в папке "git init" 

## создание сохранений

мы можем создавать "сохранения" наших версий файлов,такие сохранения называются фиксациями или коммитами.Сделать коммит можно с помощбю команды *git commit* и **обязательно** использовать флаг -m , после чего в кавычках написать сообщениею


## перемещение между сохранениями и ветками.

Чтобы перемещаться между ветками нужно ввести команду *git checkout* <имя ветки>.
 
Чтобы перемещаться между сохранениями ,нужно использовать команду *checkout* и номер коммита.

 ## Журнал изменений 
 
перемещаться между нашими сохранениями можно с помощью команды *git checkout* ,для этогоо достаточно применить команду 

можно отменить изменения с помощью команд *git revert* и *git reset* .
*git revert < номер коммита > *отменит изменения до указанной версии и создаст новый коммит.
*git revert



## отправка изменений в удаленный репозиторий

## Слияние веток и решение конфликтов

## Удаление веток
 удалить уже слитую ветку мы можем командой git branche -d 
 

## Скачивание удаленного репозитория

Чтобы скачать удаленный репозиторий нужно применить команду git pull