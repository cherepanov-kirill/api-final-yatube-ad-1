# API Yatube

REST API для социальной сети Yatube.

## Возможности

- Публикации
- Комментарии
- Группы
- Подписки
- JWT авторизация

## Стек

- Python
- Django
- Django REST Framework
- SimpleJWT

## Запуск

```bash
git clone ...
cd yatube_api

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver