# python_django

## Запуск локального сервера
```
python manage.py runserver
```
![avatar](https://i.imgur.com/2L0O1M1.png)

## Создание приложения
```
python taskmanager/manage.py startapp main
```
Добавить в taskmanager/settings.py 
```
INSTALLED_APPS = [
    'main',
```