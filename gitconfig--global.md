### GIT CONFIG --GLOBAL
---

#### **Кэширование учётных данных**

Кэшировать учётные данные можно с помощью параметра *[config](gitconfig.md "Функция git config")* с флагом `--global`. Так вы избавитесь от необходимости вручную вводить имя пользователя и пароль при создании нового коммита.

```
git config --global credential.helper cache
```
[< *К оглавлению*](readme.md)