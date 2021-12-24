Dictionaries
============

A Python dictionary is a set of key/value pairs. Python dictionaries have the requirement that the keys are unique and immutable. In other languages, dictionaries are called by various names; they are hashes in Ruby, or associative arrays in many other languages. I think that Python's term for this data structure is perfect. It provides the ideal mental image of what it is and its purpose.

.. image:: ./images/dict.jpg
    :class: logo
    :width: 400px

Python dictionaries have to have immutable keys. The reason for this is a more advanced topic, so just use strings for your dictionary keys when you are beginning.

Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Practice using the dictionary methods.
   - Try to predict the outcome of the following code. Use the Veroskills interface to test your prediction.


    .. code-block:: python
        
        person = {"name": "Daniel", "age": 25 }
        person["age"] += 1
        print(person)

    .. code-block:: python

        person = {"name": "Daniel", "age": 25 }
        person["hobbies"] = ["reading", "coding"]
        print(person)

    .. code-block:: python

        person = {"name": "Daniel", "age": 25 }
        person["address"] = {"house_number": 125, "street": "main"}
        print(person)



Further Reading
+++++++++++++++

- `Python docs: dictionaries <https://docs.python.org/3/tutorial/datastructures.html#dictionaries>`_ 