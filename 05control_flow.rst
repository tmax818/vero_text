Control Flow
============

Control flow allows different code to execute depending on a set of conditions. The keywords: :code:`if`, :code:`elif` and :code:`else` are used to control execution of code.

Run the following code in the VeroSkills editor and observe the output:

.. code-block:: python

    condition = True

    if condition:
        print("The condition is", condition)


You should see :code:`The condition is True` print. If we add the :code:`else` keyword, we can have our code perform another action in the event that our test condition is false:


.. code-block:: python

    condition = False

    if condition:
        print("The condition is", condition)
    else:
        print("The condition must be false!!!")


You should see :code:`The condition must be false!!!` print. If we add the :code:`elif` keyword, we can test another condition:


.. code-block:: python

    condition = False
    other_condition = True

    if condition:
        print("The condition is", condition)
    elif other_condition:
        print("The other condition is", other_condition)
    else:
        print("Both conditions must be false!!!")


You should see :code:`The other condition is True` print. What would print if both conditions are false?

Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Write a control flow statement that will print the word "even" if an number is even and "odd" if a number is odd.
   - Write a series of :code:`if` statements to test your understanding of logic.

    .. code-block:: python

        if True or False:
            print("if ran")
        elif True and False:
            print("elif ran")
        else:
            print("else ran")

    - change **or** and **and** in the code and try to predict the output.






Further Reading
+++++++++++++++

- `Python docs: control flow <https://docs.python.org/3/tutorial/controlflow.html>`_ 