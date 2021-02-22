# repos1
1. Создайте вирутальное окружение в корневой папке проекта (python -m venv venv)
2. Запустите вирутальное окружение: 
- venv/Scripts/activate (Windows)
- . venv/bin/activate (Linux)
3. Загрузите в него все зависимости с помощью команды pip:
- pip install django
- pip install Pillow
- pip install psycopg2 (если будете использовать Postgres в качестве БД)
4. Запустите проект локально с помощью команды python manage.py runserver
5. Введите в браузере localhost:8000/catalog/ для открытия главной страницы сайта

Если используете Postgresql в качестве БД:
1. Создайте БД Postgres
2. Задампьте файл postgres.sql в вашу БД
3. В файле settings.py измените настройки БД
