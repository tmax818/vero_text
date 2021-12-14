Functions (Part 2)
===================


.. sidebar:: Advanced Learners

    For those of you who have experience with another programming language, there is no block-scope in Python. Only functions, classes and modules create scope in Python.

Functions create scope in Python. Scope is a very important, but at times difficult to understand, concept in programming. Scope, is basically where a variable is visible to other parts of our code.


.. code-block:: python

    global_var = "global"

    def function_name():
        local_var = "local"


The :code:`global_var` variable is defined in the global scope. Defining a function in Python creates another level of scope known as the enclosing scope. In the code above, if we try to print :code:`local_var` in the global scope:

.. code-block:: python

    global_var = "global"

    def function_name():
        local_var = "local"

    print(local_var)

We will get the following error:

.. code-block:: bash

    Traceback (most recent call last):
    File "temp.py", line 4, in <module>
    print(local_var)
    NameError: name 'local_var' is not defined

The variable :code:`local_var` is not in scope.



Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Try to predict the output of the following Python code:

    .. code-block:: python

        global_var = "global"
        def function_name():
            print(global_var)
        function_name()

    .. code-block:: python

        global_var = "global"
        def outer_function():
            local_var = "local"
            def inner_function():
                print(local_var)
            inner_function()
        outer_function()




Further Reading
+++++++++++++++

- `Python docs: Built-in Functions <https://docs.python.org/3/library/functions.html>`_ 