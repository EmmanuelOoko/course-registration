# course-registration

To run locally, you will need PostgreSQL installed, and to store these variable in a .env file.

> export DB_NAME= # your db name

> export DB_USER= # your db username

> export DB_PASSWORD= # your db password

> export DEBUG_VALUE=True

Then run the following commands:

> pip install -r requirements.txt

> python3 manage.py makemigrations

> python3 manage.py migrate

> python3 manage.py runserver

Additionally, you can seed the database with the seed.json file provided like so:

> python3 manage.py loaddata seed.json
