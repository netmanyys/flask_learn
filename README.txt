virtualenv env # or python3 -m virtualenv env
source env/bin/activate
pip3 install -r requirements.txt


python3 app.py


python3
>>> from app import app
>>> with app.app_context():
...     db.create_all()
...     exit()