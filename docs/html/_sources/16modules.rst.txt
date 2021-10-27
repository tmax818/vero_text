Modules
=======

A module is a Python file. More specifically, it is a Python file that is imported into another Python file. The following code can be found in two separate Python files. The file name for the code is indicated by a comment with the file name:

.. code-block:: python
    
    ## my_module.py
    my_variable = "Hello from my_module!!!"
    def my_function():
        print("hello from my_function!!!") 

There are a few ways to use the code in `my_module.py`. The first was is as follows:

.. code-block:: python
    
    ## main.py
    import my_module

    print(my_module.my_variable)
    my_module.my_function()



Exercise
========

.. admonition:: Practice these in the Veroskills interface

   - Write a Python program that prints another string to the screen.



Further Reading
===============

- `Python website <https://python.org>`_ 