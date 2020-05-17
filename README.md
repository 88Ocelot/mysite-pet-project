# mysite-pet-project
Pet project from A. Mele book
### Installing
Create virtual env for project
```
python3.8 -m venv venv
```

Install requirements in venv

```
pip install -r requirements.txt
```
Make migrations 
```
python manage.py makemigrations
```
Apply migrtaions 
```
python manage.py migrate
```
Add secret keys from settings to env variables
