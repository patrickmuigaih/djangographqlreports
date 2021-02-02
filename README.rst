=============================
djangographqlreports
=============================

.. image:: https://badge.fury.io/py/graphql_reports.svg
    :target: https://badge.fury.io/py/graphql_reports

.. image:: https://travis-ci.org/patrickmuigaih/graphql_reports.svg?branch=master
    :target: https://travis-ci.org/patrickmuigaih/graphql_reports

.. image:: https://codecov.io/gh/patrickmuigaih/graphql_reports/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/patrickmuigaih/graphql_reports

Graphql Driven Reports

Documentation
-------------

The full documentation is at https://graphql_reports.readthedocs.io.

Quickstart
----------

Install djangographqlreports::

    pip install graphql_reports

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'graphql_reports.apps.GraphqlReportsConfig',
        ...
    )

Add djangographqlreports's URL patterns:

.. code-block:: python

    from graphql_reports import urls as graphql_reports_urls


    urlpatterns = [
        ...
        url(r'^', include(graphql_reports_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox


Development commands
---------------------

::

    pip install -r requirements_dev.txt
    invoke -l


Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
