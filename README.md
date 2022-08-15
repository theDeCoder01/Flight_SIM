To initiate the database:

python initialise_db.py

Note:
There is a "Pictures" file that contain country flags and profile pictures to use in the trial

Note2:
admin login is admin01 --> admin01 or admin02 --> admin02

Note3:
all passwords (except for admin) no less than 6 letters (as requested) and they are (12345678)

Note4:
usernames are case sensitive!


#############################################


To run the project in a vertual enviroment, start by command:

pip install -r requirements.txt

Then, since we are using Postgres:

pip install psycopg2

(Don't forget to change back the CONFIG.JSON!!!)

Then, to initiate the database:

python initialise_db.py

then, run the app:

python app.py
