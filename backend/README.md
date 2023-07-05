# Kittygram — социальная сеть для обмена фотографиями котиков. Проект состоит из бэкенд-приложения на Django и фронтенд-приложения на React.

## Описание проекта
Проект написан в рамках учебного курса по Python от Яндекс.Практикум.
Пользователи могут регистрироваться, загружать фотографии своих котов с кратким описанием, и смотреть котиков других пользователей. Основная задача  - обучение автоматизации деплоя проекта на сервер c помощью Docker.

## Технологии

 - Python 3.9
 - Django==3.2.3
 - djangorestframework==3.12.4
 - Nginx
 - gunicorn
 - docker
 - PstgreSQL

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

## Автор
Ринат Хайбуллин - [GitHub](https://github.com/haybuxx)