# A python practice project.
# This is Web practice
# By Blank

# How to use
```bash
git clone https://github.com/blankliu404/LearningLog.git
cd LearningLog

python -m venv venv
venv\Scripts\activate

pip install Django
pip install django-bootstrap3

manage.py makemigrations learning_logs
manage.py migrate

manage.py runserver
manage.py createsuperuser

# 访问localhost:8000/admin
# 访问localhost:8000