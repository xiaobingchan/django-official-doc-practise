https://docs.djangoproject.com/zh-hans/2.1/intro/tutorial01/


*****************   Django创建命令：
python django-admin.py startproject myDjango（django-admin.py startproject myDjango）
cd myDjango
python manage.py startapp learn
python manage.py runserver 127.0.0.1:8000





pip3 install Django

####  1,查看版本
python3 -m django --version

####  1,查看版本
import django
print(django.get_version())

####  2,创建项目
django-admin startproject mysite

####  3,指定监听端口
python3 manage.py runserver 8080