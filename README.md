# Flask Boilerplate

Flask Boilerplate

## Setup

````bash
git clone git@github.com:lowellbander/flask-bp.git
cd flask-bp

heroku login
heroku create $APPNAME

virtualenv venv
source venv/bin/activate

pip install -r requirements.txt

git commit -m "first commit"
git push heroku master
heroku open
````
