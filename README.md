# python_django
![avatar](https://i.imgur.com/6Uow1q4.png)
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

## Шаблоны
```
def index(request):
    return render(request, 'main/index.html')

Folder:
main/templates/main/ file
```