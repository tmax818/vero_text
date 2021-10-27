Ranges and For
==============

We skipped the `for` loop when we discussed loops becuase the `range` and the `for` loop go hand in hand. You don't have to use a range with a for loop, but it is common to do so. 

Ranges
++++++

A range is a function that generates a sequence of numbers. Run the following code inside the Veroskills interface:

.. code-block:: python

    times = range(1, 11)
                
    for item in times:
        print("Hello, World")

How many times does "Hello, World" print? This is one of the little things that you will have to remember ( or look up when you forget!!) about how Python works. You would intuitively think that "Hello, World" would print eleven times just by looking at the code. The range function generates numbers from the first integer argument up to and NOT INCLUDING the second integer argument.


Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Practice using the range function and for loop to print out all the even numbers between 1 and 100.


Further Reading
+++++++++++++++

- `Python docs: range <https://docs.python.org/3/library/functions.html#func-range>`_ 