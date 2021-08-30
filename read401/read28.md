# Django CRUD and Forms

## An HTML Form is a group of one or more fields/widgets on a web page, which can be used to collect information from users for submission to a server. 

* GET and POST are the only HTTP methods to use when dealing with forms.

* Django handles three distinct parts of the work involved in forms:

    1. preparing and restructuring data to make it ready for rendering
    2. creating HTML forms for the data
    3. receiving and processing submitted forms and data from the client

* Form data sent back to a Django website is processed by a view, generally the same view which published the form. This allows us to reuse some of the same logic.

* Creating a Django Form

Creating a form in Django is completely similar to creating a model, one needs to specify what fields would exist in the form and of what type. For example, to input, a registration form one might need First Name (CharField), Roll Number (IntegerField), and so on. 

* Render Django Forms

Django form fields have several built-in methods to ease the work of the developer but sometimes one needs to implement things manually for customizing User Interface(UI).

