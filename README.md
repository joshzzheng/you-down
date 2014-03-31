you-down
========

Working app at 

http://youdown.herokuapp.com 
(may take some time to boot up since running off of one dyno)

1. I highly recommend getting virtualenv and virtualenvwrapper installed
2. pip install all the necessary libraries: Flask, flask-restless, flask-sqlalchemy, requests
3. installing postgres: https://gist.github.com/lxneng/741932
4. run postgres
5. python runserver.py
6. open another tab (the web server needs to be running!), and do
7. python manage.py create_db, this creates the tables in the database according to models.py
8. python manage.py seed_db --seedfile 'data/seeds.json' to add the info from json file into the database
9. navigate to localhost:5000

