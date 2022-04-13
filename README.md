![](https://img.shields.io/badge/Python-3.7.5-blue) 
![](https://img.shields.io/badge/Django-2.2.16-green)
![](https://img.shields.io/badge/DjangoRestFramework-3.12.4-red)
<br><br>
# API для проекта Yatube
## Описание
#### Проект даёт возможность пользователям получать/изменять данные через API
##### Реализован функционал:

* Получить/обновить/проверить токен авторизации
* Просматривать/создавать/изменять/удалять публикации
* Просматривать/создавать/изменять/удалять комментарии к публикациям
* Просматривать список и детальную информацию о сообществах
* Подписываться на пользователя (Возможен поиск по подпискам)

## :computer: Технологии в проекте

:small_blue_diamond: Python <br>
:small_blue_diamond: Django <br>
:small_blue_diamond: Django REST Framework <br><br>

#### К API есть документация по адресу `http://localhost:8000/redoc/`
## Установка и запуск проекта

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Amaterasq/api_final_yatube.git
```

```
cd yatube_api
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source env/scripts/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
## :bust_in_silhouette: Автор проекта 

### :small_orange_diamond: Влад Перепечко _(Vlad Vi. Perepechko)_
```html
e-mail: perepechcko.vlad@ya.ru
```
```html
https://github.com/Amaterasq
```
