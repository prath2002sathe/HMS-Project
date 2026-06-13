## ⚙️ Requirements
- Python 3.x
- XAMPP (for MySQL database)
- Django

## 🔧 How to Run

1. Clone the repository
2. Start XAMPP and enable **Apache** and **MySQL**

3. Create a database in phpMyAdmin
   - Open browser → http://localhost/phpmyadmin
   - Create new database (e.g., `hms_db`)

4. Install dependencies5. Update database settings in `settings.py`
```python
   DATABASES = {
       'default': {
           'ENGINE': 'django.db.backends.mysql',
           'NAME': 'hms_db',
           'USER': 'root',
           'PASSWORD': '',
           'HOST': 'localhost',
           'PORT': '3306',
       }
   }
```

6. Run migrations
7. Start server
8. Open browser → http://127.0.0.1:8000
