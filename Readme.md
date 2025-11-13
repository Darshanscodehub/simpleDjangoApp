windows:-
pip install flask
python myapp.py

ubuntu:-
Install Python3 + pip (if not already installed):

sudo apt install python3 python3-pip -y

Install Django globally:

pip install django
sudo apt install python3-django

open settings.py file find this line:-

ALLOWED_HOSTS = []

chamnge it to:-

ALLOWED_HOSTS = ['*']


python3 manage.py runserver 0.0.0.0:8000
