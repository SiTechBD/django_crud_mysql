# django_crud_mysql
django crud using mysql

1) Install library to use mysql
   ```
   pip install django
   ```

3) Change the project settings.py database settings as like below:
   ```
   DATABASES = {
	'default': {
		'ENGINE': 'django.db.backends.mysql',
		'NAME': 'mydb',
		'USER': 'root',
		'PASSWORD': 'admin',
		'HOST':'localhost',
		'PORT':'3306',
		}
	}
```
