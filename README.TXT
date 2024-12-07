py -m venv myvenv
.\myvenv\Scripts\activate
py -m pip install --upgrade pip
pip install -r .\requirements.txt
pip install django-user-agents
py manage.py runserver