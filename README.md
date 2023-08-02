# Kittygram

### Описание проекта

Kittygram - платформа, предназначенная для того, чтобы делиться фотографиями своих котов и кошек, а также их достижениями.
**ДОБАВЛЕНИЕ ФОТОГРАФИЙ СОБАК СТРОГО ЗАПРЕЩЕНО!**

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

### URL-адрес

[https://cute-kittens.zapto.org]

### Используемые технологии

- Django
- Docker
- Python

### Автор

Проект разработан [Nikitriy](https://github.com/Nikitriy)
