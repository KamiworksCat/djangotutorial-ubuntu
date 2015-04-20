# djangotutorial-ubuntu

Following the django poll app tutorial in Django documention, "Writing your first Django app"

Completed work: <br>
Part 1 of django app tutorial <br>
Part 2 of django app tutorial <br>

In progress: <br>
Doing and attempting to comprehend part 3

# Status of part 1 tutorial: Done

Changed the timezone in mysite/settings.py from 'UTC' to 'Singapore'. (Completed) <br>
Ran manage.py migrate to create database tables for django to reference upon. (Completed) <br>
Created the polls to begin the learning journey. (Completed) <br>
Populate the models.py in polls folder with 'Questions' and 'Choice' models and migrate changes to the database. (Completed) <br>
Exploring Python Shell and adding new entry to the 'Questions' models. (Completed) <br>
New updates to models.py: adding '__str__()' and new custom method(timezone test check). (Completed) <br>
New addition to models(Choice) via Python shell: Added 2 new choices with 0 votes. (Completed) <br>

# Status of part 2 tutorial

Created user data with 'createsuperuser' command. (Completed) <br>
Edit polls/admin.py to allow the polls app to be modifiable in the admin page. (Completed) <br>
Edit the pub_date and question_text fields to exchange their positions. (Completed) <br>
Edit polls/admin.py and polls/models.py to enhance the user's UI in the admin page of the server. (Completed) <br>
Edit mysite/settings.py and added new file to tell django to source for template file and use it for the page setup. (Completed) <br>


# Status of part 3 tutorial

Create first view code in polls/views.py (Completed) <br>
Mapping the view to a URL and pointing the rool URLconf. (Completed) <br>
Adding more views and configuring their urls. (Completed) <br>
Updating index view and introducting new templates for polls to reference upon. (Completed) <br>


# Django learning points

1. Models are represented by a class(that subclasses django.db.models.Model). Each of the models has a number of class variables which represents a database field in the model.<br>

2. Django supports all common database relationships: many-to-one, many-to-many, one-to-one. <br>

3. Migrate command synchronise the changes that the user made to the models with the schema in the database. <br>

4. 'makemigrations' command bascially create migrations for the changes made in the models.py <br>

5. In 'TabularInline' mode, related objects are displayed in more compact and table-based format. <br>

6. View is a type of web page in django app that serves a specific function and has a specific template. <br>

7. In Django, web pages and other content are delivered by views. By examining the URL that is requested, Django will choose a view based on it. <br>
