![deploy workflow]
(https://github.com/DankovaAlina/kittygram_final/actions/workflows/main.yml/badge.svg)

# **Описание проекта**

Cервис обмена фотографиями котиков.
Сервис поддерживает добавление новых записей от лица пользователя с фотографией и описанием.

Проект поддерживает развертку в Docker-контейнерах.

# **Стек технологий**

Python 3.9.6
Django 3.2.3
Django REST Framework 3.12.4

# **Как запустить проект локально**

### **Клонировать репозиторий и перейти в него в командной строке:**

```
git clone https://github.com/DankovaAlina/kittygram_final
cd kittygram_final
```

### **Cоздать и активировать виртуальное окружение:**

```
python3 -m venv env
source env/bin/activate
```

### **Установить зависимости из файла requirements.txt:**

```
python3 -m pip install --upgrade pip
cd backend
pip install -r requirements.txt
```

### **Выполнить миграции:**

```
python3 manage.py migrate
```

### **Запустить проект:**

```
python3 manage.py runserver
```

# **Структура файла .env**

USE_POSTGRES - bool - флаг использования PostgreSQL или SQLite
POSTGRES_USER - str - логин пользователя в PostgreSQL
POSTGRES_PASSWORD - str - пароль пользователя в PostgreSQL
POSTGRES_DB - str - название БД в PostgreSQL
DB_HOST - str - название хоста в PostgreSQL
DB_PORT - int - порт PostgreSQL
SECRET_KEY - str - ключ шифрования
DEBUG - bool - флаг использования режима отладки
ALLOWED_HOSTS - str - разрешенные хосты с разделителем через запятую ('localhost,127.0.0.1')

# **Автор**

@DankovaAlina
