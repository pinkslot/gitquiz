### Тест по vcs git
Для выполнения работы вам понадобится аккаунт github.
Задания:

- создать локальный репозиторий
- создать файл file1.txt, добавить в него строчку с вашим именем (не забудьте поддерживать пустую строку в конце файла), добавить файл к репозиторию, сделать коммит
- сделать второй коммит*
- поставить tag t1
- изменить последний коммит, заменив в нём строку "commit 2" на "commit 3" и поменяв сообщение
- выполнить слияние(merge) master c t1, разрешив конфликт, добавлением строки "commit 3", после "commit 2"
- сделать 4ый коммит
- добавить новый файл file2.txt к репозиторию, сделать коммит
- переименовать file2.txt в file3.txt, сделать коммит с переименованием
- перейти к 4ому коммиту, создать ветку branch1
- изменить строчку "commit 4" на "changed commit", сделать коммит
- перейти в ветку master, сделать rebase на branch1
- изменить состояние ветки branch1 до состояния ветки master
- перейти к ветке master, изменить её историю, добавив *перед* 4ым коммитом, еще один коммит, заменяющий строку "commit 2" на "another changed commit"
- заменить коммиты с добавлением file2.txt и переименованием в file3.txt, на один - добавление file3.txt
- сделать fork https://github.com/gitquiz/quiz, добавить *ваш* удалённый репозиторий в список remote вашего локального репозитория под именем my_remote
- забрать изменения ветки my_remote/master с удалённого репозитория, слить её с локальной веткой master
- отправить изменения локальный ветки master в ветку master удалённого репозитория
- выполнить rebase branch1 с origin/master, не потеряв коммита merge master t1 
- отправить локальную ветку branch1 в ветку another_branch_name удалённого репозитория
- отправить pull request ветки master в https://github.com/gitquiz/quiz

*Коммиты типа n-ый коммит - заключаются в добавлении новой строчки с текстом "commit n" в file1.txt.
