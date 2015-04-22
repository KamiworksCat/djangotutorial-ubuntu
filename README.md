# djangotutorial-ubuntu

Following the django poll app tutorial in Django documention, "Writing your first Django app"
Attempting to finish the tutorial while trying to understand the way django programming language works.

Completed work: <br>
Part 1 of django app tutorial <br>
Part 2 of django app tutorial <br>
Part 3 of django app tutorial <br>

In progress: <br>
Doing and attempting to comprehend part 4

# Status of part 1 tutorial: Done

Changed the timezone in mysite/settings.py from 'UTC' to 'Singapore'. (Completed) <br>
Ran manage.py migrate to create database tables for django to reference upon. (Completed) <br>
Created the polls to begin the learning journey. (Completed) <br>
Populate the models.py in polls folder with 'Questions' and 'Choice' models and migrate changes to the database. (Completed) <br>
Exploring Python Shell and adding new entry to the 'Questions' models. (Completed) <br>
New updates to models.py: adding '__ str __ ()' and new custom method(timezone test check). (Completed) <br>
New addition to models(Choice) via Python shell: Added 2 new choices with 0 votes. (Completed) <br>

# Status of part 2 tutorial: Done

Created user data with 'createsuperuser' command. (Completed) <br>
Edit polls/admin.py to allow the polls app to be modifiable in the admin page. (Completed) <br>
Edit the pub_date and question_text fields to exchange their positions. (Completed) <br>
Edit polls/admin.py and polls/models.py to enhance the user's UI in the admin page of the server. (Completed) <br>
Edit mysite/settings.py and added new file to tell django to source for template file and use it for the page setup. (Completed) <br>


# Status of part 3 tutorial: Done

Create first view code in polls/views.py (Completed) <br>
Mapping the view to a URL and pointing the rool URLconf. (Completed) <br>
Adding more views and configuring their urls. (Completed) <br>
Updating index view and introducting new templates for polls to reference upon. (Completed) <br>
Create Http404 request and exception in views.py and new detail.html for polls/templates. (Completed) <br>
Updating detail.html with more enhancement. (Completed) <br>
Removing hardcoded url in index.html. (Completed) <br>
Namespacing url names. (Completed) <br>

# Status of part 4 tutorial

Enhance the outlook in detail.html (Completed) <br>


# Django learning points

1. Models are represented by a class(that subclasses django.db.models.Model). Each of the models has a number of class variables which represents a database field in the model.<br>

2. Django supports all common database relationships: many-to-one, many-to-many, one-to-one. <br>

3. Migrate command synchronise the changes that the user made to the models with the schema in the database. <br>

4. 'makemigrations' command bascially create migrations for the changes made in the models.py <br>

5. In 'TabularInline' mode, related objects are displayed in more compact and table-based format. <br>

6. View is a type of web page in django app that serves a specific function and has a specific template. <br>

7. In Django, web pages and other content are delivered by views. By examining the URL that is requested, Django will choose a view based on it. <br>

8. get_object_or_404() help coupled the model layer to view layer. <br>

9. get_list_or_404() function use filter() instead of get() but works the same as get_object_or_404(). <br>

10. The template system uses dot-lookup syntax to access variable attributes. <br>

11. Adding namespace to root URLconf helps to differentiate one app from other apps that has similar view. <br>

12. It is recommended to use method="post" whenever you create a form which will influence data server-side. <br>

