# LibraryManagmentSystem

HOW TO RUN THIS PROJECT
Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
Open Terminal and Execute Following Commands :

python manage.py runserver

http://127.0.0.1:8000/


CHANGES REQUIRED FOR CONTACT US PAGE
In settins.py file, You have to give your email and password
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'


## To create a superuser go to cmd prompt

python manage.py createsuperuser

give username
give email
give password
enter password again 

## To create a staff

Go to superuser and create a user and add it into admin group and give permissions.


## already existed staff :

username : staff12

password : Admin123@

