#API YATUBE

Реализованными API можно создавать/читать посты, добавлять/читать комментарии к постам, выгружать сообщества и подписки на авторов.

Технологии

Django, djangorestframework, djangorestframework_simplejwt

Запуск в dev-сервера:

1)Клонировать репозиторий,
2)Установите и активируйте виртуальное окружение,
3)Установите зависимости из файла requirements.txt
4)Перейдите в каталог с файлом yatube/manage.py выполните команды: 
  1)python manage.py migrate,
  2)python manage.py createsuperuser,
  3)python manage.py runserver
