{% if False %}

django_app_template

This is a template for creating a new reusable application for Django. This uses the template feature added to the startapp command in Django 1.4. While creating the app requires using Django 1.4 you can choose to support earlier versions once it has been created.

To start a new app with this template:

# Install Django
pip install django>=1.4
django-admin.py startapp --template=https://github.com/presencelearning/django-app-template/zipball/master --extension=py,rst,in <app_name>
Note

This template uses defaults and best practices used at PresenceLearning.

{% endif %}
{{ app_name }}
========================

Welcome to the documentation for django-{{ app_name }}!


Running the Tests
------------------------------------

You can run the tests with via::

    python setup.py test

or::

    python runtests.py