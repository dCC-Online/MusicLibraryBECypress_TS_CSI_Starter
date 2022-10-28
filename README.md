# Music Library Backend (Starter) for Cypress Testing on Frontend 

On the chance that a student does not have a completed Music Library project to use for Cypress testing, we are offering a complete version of both the frontend and a COMPATIBLE backend. 

To use this backend:

In MySQL workbench, create a new database using the SQL command 'create database musiclibrary_cypress'

Open this project in VS Code (open the folder that contains the Pipfile as outermost directory).

Copy the local_settings.py file you used in your own project into the musiclibrary/musiclibrary folder.

Change the database name in local_settings.py to 'musiclibrary_cypress'

Run terminal commands in VS Code:
(Be sure you are in same directory as Pipfile before doing this)
pipenv install
pipenv shell
python manage.py migrate
python manage.py runserver

Use Postman or the React app to seed some Songs!
