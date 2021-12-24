Logic
=====

There are three main logical operators in Python: :code:`not`, :code:`and`, and :code:`or`. These logical operators play a pivotal role in writing code that is responsive and dynamic.

Not
****

The not operator is like flipping a switch. Whatever an expression evaluates to, applying the :code:`not` operator converts it to its opposite.

.. csv-table:: :code:`not`
    :header: :code:`p`, :code:`not p`
    :widths: 10, 10

    :code:`True`, :code:`False`
    :code:`False`, :code:`True`



And 
*****

The only way an :code:`and` statement is true is if both expressions are true. Otherwise, it is false.

.. csv-table:: :code:`and`
    :header: :code:`p`, :code:`q`, :code:`p and q`
    :widths: 10, 10, 10

    :code:`True`, :code:`True`, :code:`True`
    :code:`True`, :code:`False`, :code:`False`
    :code:`False`, :code:`True`, :code:`False`
    :code:`False`, :code:`False`, :code:`False`

Or 
******

The only way an :code:`or` statement is false is if both expressions are false. Otherwise, it is true.

.. csv-table:: :code:`or`
    :header: :code:`p`, :code:`q`, :code:`p or q`
    :widths: 10, 10, 10

    :code:`True`, :code:`True`, :code:`True`
    :code:`True`, :code:`False`, :code:`True`
    :code:`False`, :code:`True`, :code:`True`
    :code:`False`, :code:`False`, :code:`False`

Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Write a Python expression that evaluates to True.
   - Use parentheses and convert the Python expression you wrote in the last exercise and make sure it evaluates to false.
   - Use the Veroskills interface to access the Python help documentation.
   - Try to predict the outcome of the following Python expressions:

    .. code-block:: python
        
        print(True or False)

    .. code-block:: python

        print(True and False)

    .. code-block:: python

        print(True and (4 == 5))

    .. code-block:: python

        print(not False and True)


Further Reading
+++++++++++++++

- `Python logical operators <https://www.w3schools.com/python/python_operators.asp>`_ 