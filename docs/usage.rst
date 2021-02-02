=====
Usage
=====

To use djangographqlreports in a project, add it to your `INSTALLED_APPS`:

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
