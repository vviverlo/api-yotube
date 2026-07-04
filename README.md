# Yatube API
Проект API для социальной сети «Yatube».  
В рамках проекта реализован API для моделей: Post, Group, Comment, Follow.

# Технологии, использованные в проекте
- Python  
- Django  
- Django REST Framework  
- djoser (JWT аутентификация)  
- SQLite (база данных по умолчанию)  
- Git (система контроля версий)  
- Docker (опционально, если используется)  
- Postman / HTTP клиент для тестирования API

# Установка
Клонируйте репозиторий:
```bash
git clone https://github.com/vviverlo/api-final-yatube
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

Автор:
Ислам Рамазанов
