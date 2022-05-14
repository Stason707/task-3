[Вернуться к содержанию](./readme.md)
# git init

## Зачем нужна команда git init

Init - это сокращение от <initialize> (т.е. "инициализироать" или "включать", "запускать"). Это значит, что когда Вы пишете ```git init```, Git "включается" или "запускается" для данного репозитория (т.е. папки).
## Что происходит в момент "включения"?

Git создает в указанной папке скрытую папку ***.git***. В этой папке хранятся служебные файлы Git. Если её удалить, то Git уже не будет "видеть" эту папку, то есть если написать ```git status```, Git нам ответит, что это "***не Git репозиторий***").

Зачем нужна эта команда? Это - одна из нескольких команд, с которой можно начать работу с Git. Например, если Вы создаете проект у себя на компьютере, а потом уже хотите его отправить на удаленный репозиторий, то Вам пригодится эта команда.

```bash=
 git init
```
---