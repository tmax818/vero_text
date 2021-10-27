The Python Standard Library
===========================

The `Python Standard Library <https://docs.python.org/3/library/>`_ is what makes Python a "batteries included" language. The Standard Library has code for handling just about anything. The following code will open the webpage for the Standard Library using a module, :code::`webbrowser`  from the Standard Library!

.. code-block:: python

    import webbrowser
    webbrowser.open("https://docs.python.org/3/library/")

The following code will print a calendar for the year 2021:

.. code-block:: python

    import calendar

    print(calendar.calendar(2021))