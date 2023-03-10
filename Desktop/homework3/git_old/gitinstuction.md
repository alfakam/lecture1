# Инструкция ГИТ начало
# Лекция 1

Создали файл **Instruction.md**

Выполняем команду *git init* (инициалиция локального репозитория)

Выполняем команду *git add* (добавление файла)

Затем *git status* (текущее сосотояние гита)


Выполняем команду *git commit* -m "..."(зафиксировать или сохранить)

### Еще пару основных команд:
+ git log - журнал изменений
+ git checkout - переключение между версиями
+ git diff - показывает разницу между текущим и сохраненным  

# Лекция 2

Команда *git branch* позволяет создавать, просматривать, переименовывать и удалять ветки.
+ *git branch -d "branch"* - удаление указанной ветки.
+ *git branch -D "branch"* - принудительное удаление указанной ветки, даже если в ней есть неслитые изменения.
+ *git branch -m "branch"* - изменение имени текущей ветки
+ *git branch -a* -Вывод списка всех удаленных веток.

В *Git* под термином *checkout* подразумевают переключение между различными версиями целевого объекта. 

Команда *git merge* выполняет слияние отдельных направлений разработки.

# Лекция 3.

# Удаленные репозитории.

Команду *git clone* выполняют для создания копии (клонирования) удаленного репозитория. 

В качестве параметра в команду *git clone* передается URL-адрес репозитория.

По умолчанию команда *git remote* отображает ранее сохраненные удаленные подключения к другим репозиториям.

Команда *git push* используется для выгрузки содержимого локального репозитория в удаленный репозиторий.

Команды *git fetch* и *git pull* можно рассматривать как команды загрузки (скачивания).

**Конец**
