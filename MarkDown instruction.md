# Памятка Markdown | Syntax | Git 
_В данном разделе я публикую полезную информацию по работе с репозиториями_


## Основные команды:
* git init - началот работы
* git status - проверить статус
* git add (название файла) - сохранить/подгрузить
* git commit фикация
* git commit -m "текст комментария об изменениях"
* git log - проверить журнал/история изменений
* git diff - чем отличаются версси
* git branch - ветка в которой работаешь (main/master)
* git merge (ветку) - сливает версии в одну (в которой находишся)
* git checkout (ветка) - переключает между версиями файла
* git checkout - касса файл инфо
* clear - очистить терминал
* git branch -D (ветка) - удаляет ветку групбо
* git branch -d (ветка) - удаляет ветку аккуратно

## Удаленный репозиторий
Порядок запушивания:
1. git remote add origin https://github.com/SytinYura/GeekB-Les.git
2.
3.
4.

Подключаемся и выгружаем в репозеторий:
1. git remote add origin https://github.com/SytinYura/GeekB-Les.git
2. git branch -M main
3. git push -u origin main (закачиваем в репозиторий)

Команды для работы с репозиторием:
* git push (закачиваем)
* git pull (сливаем - обновляем свой репозиторий)
* git clone _ссылка_ - копир создание копии

Ошибки и решения:
* git remote rm origin -удалить ремоде
* git remote add origin _ссылка_ - добавить новый
* git pull - если удаленный репозиторий имеет коммиты (_ошибка: Git fatal: remote origin already exists_), которых нет на локальной машине. нужно  их слить через git pull для начала

Если при таких командах и последовательностях ошибка: 
* git branch -M main
* git push -u origin main
* --ошибка---
* error: src refspec main does not match any
* error: failed to push some refs to ...

Решение:
* git commit -m "first commit"
* git branch -M main
* git remote add origin ___ссылка на репу___
* git push -u origin main

(возможно придется создать новый репозиторий)

## Таблицы
Раздел в разработке

## Работа с Jpg / Png / Svg
Несколько моих работ по UX/UI дизайну 
![Дизайн сайта ОгоРодина](https://sitini.ru/img/Web_sitini_14.jpg)
![Дизайн сайта ОгоРодина](https://sitini.ru/img/Web_sitini_15.jpg)

## Работа с сылками
Другие мои работы вы можете посмотреть на сайте [sitini - творческая IT-команда](https://sitini.ru/).

## Заключение
Дополнительную информацию можно найти в разделе https://docs.github.com/

@sytinyura: буду и дальше обновлять раздел! :shipit:

