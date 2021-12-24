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

The syntax ``my_module.my_variable`` involves using what is known as a **namespace**. The ``my_module`` before the variable and function name is the namespace. This is required when the simple ``import my_module`` syntax is used. The other way is a bit more popular, but both methods have their use cases.

.. code-block:: python
    
    ## main.py
    from my_module import my_function, my_variable

    print(my_variable)
    my_function()

This is a bit cleaner and easier to understand. If you find namespaces confusing, use the second syntax.


Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Write a Python program that imports modules from the Standard Library.



Further Reading
+++++++++++++++

- `Python modules <https://docs.python.org/3/tutorial/modules.html>`_ 