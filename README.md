# just_ege
Репозиторий гита для обсидиана.
Для использования надо установить git и obsidian

[Прикольные выноски](https://help.obsidian.md/Editing+and+formatting/Callouts/)

Первый запуск:

    После создать папку где будут лежать файлы и зайти туда с помощью cmd и команды cd
    Например вы создали папку на рабочем столе с именем ege 
    cd Desktop/ege

    Далее:
        git init
        git config --global user.name "здесь ник на гит хаб"
        git config --global user.email "здесь почта с гит хаба"
    
    попросить добавить меня вас (скинуть ник в вк)
    
    git remote add origin https://github.com/MeKiGiWi/just_ege
    git pull origin master

    В обсидиане выбрать пункт открыт папку как хранилище, после выбрать папку где 
    был git init и там выбрать нужный предмет

Дальнейшее использование:

    Как только зашли в консоль cd путь_с_вашей_папкой
    git pull origin master

    Если не работает:
        git add .
        git stash

    Для добавления ваших изменений:
        git add .
        git commit -m "ТУТ ОПИСАНИЕ ТОГО ЧТО ДОБАВЛЕНО, пожайлуста хотя бы одно предложение"
        git push origin master

    Obsidian:
        ```python
        Тут блок кода на языке пайтон
        ```
        `Тут маленький блок кода` ` << этот знак где буква ё на англ

        Ю 
        > [!callout name] все каллоуты внизу

        В найстройках сочетания клавиш включите тэг подсветка и выделение
        например на ctrl + space, после выделяете
        текст и нажимаете сочетание чтобы выделить текст

        ctrl + B жирный

        ctrl + I курсив

        [имя другой заметки] - создает связь с заметкой на графе

        ctrl + g показывает граф

        
        #тема например #циклы ПИШЕМ ВНИЗУ ЗАМЕТКИ если это тема заметки маленькая можно забить
        

