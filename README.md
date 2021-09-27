# Ваше задание

## Перед началом

1. Зарегистрируйтесь на GitHub, если вы ещё не.
2. Прочтите инструкцию и взгляните на картинку, чтобы точно всё понять. Если будут вопросы — задавайте в чате.

## Инструкция

1. Склонируйте этот репозиторий
2. В репозитории есть ветка template, но последний коммит в ней бесполезен — всю информацию по ошибке удалили. Вам нужен предыдущий коммит.

   Вам надо:
   1. Выяснить SHA этого коммита. SHA — это хеш коммита, т.е. его идентификатор.
   2. Завести свою ветку так, чтобы она указывала на этот коммит. В качестве имени ветки укажите свой логин на github.

      Вы можете создать ветку прям из этого коммита, или из любого другого, а затем перенести указатель своей ветки. В общем, заведите свою ветку так, чтобы она указывала именно на этот коммит, а значит новые коммиты в вашей ветке будут дочерними.
3. Когда вы переключитесь на этот коммит, появится папка `homework` с файлом `template.txt`.
   На первой строчке в нём будет написано `<commit_sha>` и текст Lorem Ipsum.

   Вам надо:
   1. Переименовать этот файл заменив имя файла `template.txt` на ваш логин, вот так: `<login>.txt`.
   2. В самом файле заменить `<commit_sha>` на хеш, коммита, который вы выяснили ранее.
   3. Внесённые изменения не забывайте сохранять — т.е. коммитить. Вы можете сделать один коммит или несколько, как вам угодно.
4. Отправьте свои изменения на сервере, т.е. сделайте push.
6. Сделайте пулл-реквест из своей ветки в ветку `homework`. НЕ `master`, а `homework`!

![здесь должна быть инструкция](instruction.jpg)