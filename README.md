# Simple Django JWT Authorization
All what you have to run this project is:
1. Install python requirements
```bash
pip install -r requirements.txt 
```
2. Migrate Django
```bash
python manage.py migrate 
```
3. Create Django's user
```bash
python manage.py createsuperuser
```
4. Serve Django
```bash
python manage.py runserver
```

Authorization should be available on [127.0.0.1:8000/api/token/](http://127.0.0.1:8000/api/token/)