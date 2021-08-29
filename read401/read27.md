# Django Models

* Models are usually defined in an application's models.py file. They are implemented as subclasses of django.db.models.Model, and can include fields, methods and metadata.

* A model can have an arbitrary number of fields, of any type — each one represents a column of data that we want to store in one of our database tables. Each database record (row) will consist of one of each field value.

* Once you've defined your model classes you can use them to create, update, or delete records, and to run queries to get all records or particular subsets of records. 

* In order to log into the admin site, we need a user account with Staff status enabled. In order to view and create records we also need this user to have permissions to manage all our objects.  You can create a "superuser" account that has full access to the site and all needed permissions using manage.py.

* Django does a pretty good job of creating a basic admin site using the information from the registered models:

    1. Each model has a list of individual records, identified by the string created with the model's __str__() method, and linked to detail views/forms for editing. By default, this view has an action menu at the top that you can use to perform bulk delete operations on records.

    2. The model detail record forms for editing and adding records contain all the fields in the model, laid out vertically in their declaration order.  

* The handler is the engine that determines what happens to each message in a logger. It describes a particular logging behavior, such as writing a message to the screen, to a file, or to a network socket.

* A filter is used to provide additional control over which log records are passed from logger to handler.

* Django uses the standard Python logging facilities.

* Logging settings are set through the logging.dictConfig dictionary.

* Django provides a few logging extensions for handling common web server issues.