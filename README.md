# test-task-idaproject
Это сервис, который позволяет загружать изображения с компьютера пользователя, или по ссылке, а затем изменять их размер.

## Инструкция по развёртыванию.

1. Создайте и заполните файл .env в папке idaproject.
```
copy idaproject\.env.default idaproject\.env
```

2. Сгенерируйте SECRET_KEY или получите его по [ссылке](https://djecrety.ir/).

3. Создайте и активируйте виртуальное окружение
```
python -m venv venv
"venv/Scripts/activate"
```

4. Установите зависимости
```
pip install -r requirements.txt
```

5. Запустите тесты.
```
python manage.py test
```

6. Сделайте миграции и запустите проект.
```
python manage.py migrate
python manage.py runserver
```

7. Проект доступен по адресу 127.0.0.1:8000
