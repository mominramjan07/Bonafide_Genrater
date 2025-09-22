VMC - Bonafide Certificate Generator (Django)
--------------------------------------------
Quick start:
1. Create a Python virtualenv and activate it
   python -m venv env
   source env/bin/activate   # or env\Scripts\activate on Windows
2. Install requirements:
   pip install -r requirements.txt
3. Run migrations and start server:
   python manage.py migrate
   python manage.py runserver
4. Open http://127.0.0.1:8000/ to access the student form.

Notes:
- This project uses SQLite by default.
- QR codes are generated into the media/qrcodes/ directory.
- For production, set DEBUG=False and configure SECRET_KEY and ALLOWED_HOSTS properly.
