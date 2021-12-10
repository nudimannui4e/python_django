## python_django
![avatar](https://i.imgur.com/QS72Jez.png)
![avatar](https://i.imgur.com/KeR7wbC.png)

Делалось по уроку:
https://www.youtube.com/watch?v=6K83dgjkQNw

### Запуск локального сервера
```
python manage.py runserver
```
![avatar](https://i.imgur.com/2L0O1M1.png)

### Создание приложения
```
python taskmanager/manage.py startapp main
```
Добавить в taskmanager/settings.py 
```
INSTALLED_APPS = [
    'main',
```

### Шаблоны
```
def index(request):
    return render(request, 'main/index.html')

Folder:
main/templates/main/ file
```
### Создать БД и мигрировать ее
```
python taskmanager/manage.py makemigrations
python taskmanager/manage.py migrate
```

### Создать пользователя
```
python taskmanager/manage.py createsuperuser
```