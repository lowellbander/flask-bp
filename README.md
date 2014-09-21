# Flask Boilerplate

Flask Boilerplate

## Setup

````bash
git clone git@github.com:lowellbander/flask-bp.git
cd flask-bp

virtualenv venv
source venv/bin/activate

pip install -r requirements.txt
````

### To Run Locally:

````bash
# Install foreman and then run
foreman start
````

### To Run On Heroku:

````bash
heroku login
heroku create $APPNAME
git push heroku master
heroku open
````
