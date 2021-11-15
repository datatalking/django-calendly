# django-calendly
## About
A Calendar Slot Booking service, similar to that of Calendly, which allows people to define their available slots on a day and other people to book them.
The server of this application is built on the Python framework Django.

## Setup
Run the following commands to setup the application on your machine:
```bash
./server-setup.sh
source pyenv/bin/activate
python manage.py migrate
```
## Start the server
1. Activate the virtual environment by running the command:
    ```bash
    source pyenv/bin/activate
    ```
2. Start the Django Server by running the command:
    ```bash
    python manage.py runserver
    ```
    The application starts listening on http://127.0.0.1:8000/.
3. Error 403 or 404 depending upon package

## Author
Akash Agrawal

## Post Author Notes
Andrew Schell
errors on runserver, migrate and other packages not installing.
```angular2html
conda activate /Users/xxxxxxxx/opt/anaconda3/envs/django-calendly
/Users/xxxxxxxx/opt/anaconda3/bin/conda install -p /Users/wadewilson/opt/anaconda3/envs/django-calendly djangorestframework -y
```
# tried pip3 install psycopg2==2.7.5
# made progress
# error django_heroku error not found, depreicated in favor of django_on_heroku
# tried sudo apt install libpq-dev
# no go, not debian, tried brew install libpq-dev after pip install libpq-dev
# then tried brew install libpq
# will retry then brew postgresql-upgrade-database

