# Python Flask authentication boilerplate

based on:
[DigitalOcean Article](https://www.digitalocean.com/community/tutorials/how-to-add-authentication-to-your-app-with-flask-login)
by Anthony Herbert

Usage:

```
python3 -m venv auth
source auth/bin/activate
export FLASK_APP=project
export FLASK_DEBUG=1
```
Python REPL;
```
from project import db, create_app
db.create_all(app=create_app())
```

`flask run`

Libs used:
`flask flask-sqlalchemy flask-login`

Enjoy ;-)
