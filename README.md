# djangotutorial-ubuntu

Following the django poll app tutorial in Django documention, "Writing your first Django app"

Completed work: <br>
Part 1 of django app tutorial <br>

In progress: <br>
Doing and attempting to comprehend part 2 <br>

# Status of part 1 tutorial: Done

Changed the timezone in mysite/settings.py from 'UTC' to 'Singapore'. (Completed) <br>
Ran manage.py migrate to create database tables for django to reference upon. (Completed) <br>
Created the polls to begin the learning journey. (Completed) <br>
Populate the models.py in polls folder with 'Questions' and 'Choice' models and migrate changes to the database. (Completed) <br>
Exploring Python Shell and adding new entry to the 'Questions' models. (Completed) <br>
New updates to models.py: adding '__str__()' and new custom method(timezone test check). (Completed) <br>
New addition to models(Choice) via Python shell: Added 2 new choices with 0 votes. (Completed) <br>

# Django learning points

1. Models are represented by a class(that subclasses django.db.models.Model). Each of the models has a number of class variables which represents a database field in the model.<br>

2. Django supports all common database relationships: many-to-one, many-to-many, one-to-one. <br>

3. Migrate command synchronise the changes that the user made to the models with the schema in the database. <br>

4. 'makemigrations' command bascially create migrations for the changes made in the models.py <br>
