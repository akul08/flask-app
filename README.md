# Flask app

 - heroku login
 - mkvirtualenv flask-app
 - workon flask-app
 - pip install flask
 - create app.py
 - create templates folder & templates/index.html
 - pip freeze > requirements.txt
 - create Procfile
 - web: python app.py
 - git init
 - ga .
 - gc -m "flask app deployed"
 - heroku create
 - heroku apps:rename flaskapp
 - git push heroku master
 - heroku ps:scale web=1
 - heroku ps
 - heroku open
