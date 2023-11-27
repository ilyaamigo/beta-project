# Шпаргалка по работе с GIT

1. Скачать GIT
2. Создать репозиторий через команду **mkdir**
3. Инициализировать репозитоорий через команду **git init**
4. Зарегистироваться на GitHub
5. Создать новый репозиторий на GitHub
6. Создать SSH-ключ
7. Связать локальный и удаленный репозитории через команду **git remote add**
8. Синхронизировать изменения между репозиториями через команду **git push**

## Главные понятия:

Git преобразует информацию о коммитах с помощью алгоритма SHA-1 и для каждого из них рассчитывает уникальный идентификатор — хеш. <\br>
Хеш — основной идентификатор коммита и позволяет узнать его автора, дату и содержимое закоммиченных файлов. <\br>

## Основные команды:

* __cd__ - переход по папкам и директориям
* __ls__ - посмотреть все файлы и папки в текущей папке
* __touch__ - создание файла в текущей папке
* __cp__ - копирование
* __mv__ - перемещение
* __cat__ - чтение
* __rm__ - удаление файла
* __rmdir__ - удаление папки
* __git status__ - текущее состояние проекта: есть ли незакоммиченные (изменённые) файлы и название текущей ветки
* __git add__ - подготовка файлов к сохранению
* __git commit -m__ - сохранение изменений в файлах (**самая важная команда**)
* __git log__ - история коммитов