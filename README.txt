virtualenv env
source env/bin/activiate
pip3 install -r requirements.txt


python3 app.py


python3
>>> from app import app
>>> with app.app_context():
...     db.create_all()
...     exit()