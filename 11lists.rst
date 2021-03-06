Lists
=====

Python lists are an indexed, mutable sequence of comma-separated items.

.. code-block:: python

    my_list = [True, 42, 3.14, 75]

Python lists can contain a mix of different data types. The list above contains a Boolean, two integers and a float. Run the following code in the Veroskills interface:

.. code-block:: python

    help(list)

Scroll down and find the list methods that don't have a double underscore on the beginning and end of the method name. Practice with as many of these methods as you can.

Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Practice using as many of the list methods as you can.
   - Try to predict the outcome of the following code. Use the Veroskills interface to test your prediction.


    .. code-block:: python
        
        my_list = [1,2,3,4]
        my_list.append("5")
        print(my_list)

    .. code-block:: python

        my_list = [1,2,3,4]
        item = my_list.pop(4)
        print(item)

    .. code-block:: python

        my_list = [1,2,3,4]
        item = my_list.pop(1)
        print(item)




Further Reading
+++++++++++++++

- `Python docs: More on Lists <https://docs.python.org/3/tutorial/datastructures.html#more-on-lists>`_ 