Tuples
======

A tuple is an immutable sequence of comma-separated objects. 


.. code-block:: python

    my_tuple = (True, True, True, False, "Tyler", 39)

Python tuples can contain a mix of different data types. The tuple above contains several Booleans, a string and an integer. Run the following code in the Veroskills interface:

.. code-block:: python

    help(tuple)

Scroll down and find the list methods that don't have a double underscore on the beginning and end of the method name. You will notice how few methods tuples have compared to lists. 



Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Practice using as many of the tuple methods as you can.
   - Try to predict the outcome of the following code. Use the Veroskills interface to test your prediction.


    .. code-block:: python
        
        my_tuple = (1,2,3,4)
        my_list.append("5")
        print(my_tuple)

    .. code-block:: python

        my_tuple = (1,2,3,4)
        item = my_tuple.pop(4)
        print(item)

    .. code-block:: python

        my_tuple = [1,2,3,4]
        item = my_tuple.index(1)
        print(item)



Further Reading
+++++++++++++++

- `Python docs: Tuples and Sequences <https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences>`_ 