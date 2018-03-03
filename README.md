# web readme
## Instructions for running the web client (node) and backend server (flask)

Sorry this is all a bit messy right now.

To start running the flask server, ideally spin up a virtual env, then install
the requirements:

```
$ cd bairon/web/flask-backend/
$ virtualenv venv
$ . venv/bin/activate
$ pip install -r requirements.txt
```

Then,

```
$ flask run
```

For me this runs on 127.0.0.1:5000 by default, and that's hard coded in App.js
(sorry sorry). If yours is on a different port you might have to change this
behavior as well.

New terminal tab,

```
$ cd ../bairon/
$ npm install
$ npm start
```
