Yatube API

Проект API для социальной сети «Yatube».  
В рамках проекта реализован API для моделей: Post, Group, Comment, Follow.

Технологии

Python 3.12
Django 5.x
Django REST Framework
djoser (JWT аутентификация)

Установка

Клонируйте репозиторий:

```bash git clone <repository-url>
cd api-final-yatube

Создайте и активируйте виртуальное окружение:
python -m venv env
source env/bin/activate 

Установите зависимости:
pip install -r requirements.txt

Примените миграции:
python manage.py migrate

Создайте суперпользователя (если нужно):
python manage.py createsuperuser

Запустите сервер:
python manage.py runserver

API доступно по адресу:
http://127.0.0.1:8000/api/v1/

Документация (Redoc):
http://127.0.0.1:8000/redoc/