# Blog Website Using Django

#### Main Features:
* User/Author can Login or Signup initially.
* After Logging In USer can then Create a Blog with Title, Main Body and Thumbnail of their choice and  Publish it on the main page.
* User can Also view other Articles of Different Users. 

## To run this project follow the instructions given below:

#### First Clone the project
```
git clone https://github.com/altamash23820/django-blog
cd blog_app
```

#### After cloning, run following commands:-
```
pip install django[argon2]
pip install Pillow==2.2.1
```
#### After running commands use following commands:
```
python manage.py migrate
python manage.py makemigrations
python manage.py migrate
```

#### Once done with that create a superuser account:
```
python manage.py createsuperuser
```

#### Once superuser account is created we can run the website
```
python manage.py runserver
```

#### If there are no errors website will be running on [http://127.0.0.1:8000/](http://127.0.0.1:8000/) (default)