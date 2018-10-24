Flask QUIZ APP Version 18.0

GENERAL USAGE NOTES
-------------------
Ensure the presence of the following Python libraries:

- SQLALCHEMY
- FLASK
- FLASK_SQLALCHEMY
- SHA256_CRYPT

GETTING STARTED
---------------
Boot up the terminal, and get into the Flask app directory.
Run the following commands:

1. `python dummy.py`
2. `python database.py`

Now the web app is hosted at http://localhost:5000/


WORKING AND FUNCTIONALITIES:
----------------------------
This app runs on python 2.7, using Flask and SQLite. By running dummy.py we make a base SQL database and we begin the program.

The following functionalities have been implemented:

-Ability to take a quiz and view the corresponding leaderboard

-State restoration such that by logging out in between, we can continue quiz on logging back

-Admin can add and modify quizzes under subtopics

-A 50-50 helpine feature

-User can view user related information at the profile page

-Quizzes feature single correct and multiple correct types 

