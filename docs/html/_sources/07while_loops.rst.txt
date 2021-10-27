While Loops
===========

The first virtue of a programmer is laziness. Loops allow us to let a computer do boring or repetitive tasks for us. What could be more boring and repetitive than counting? We can use Python to count to 500 in the blink of an eye:

.. code-block:: python

    count = 500

    while count > 0:
        print("The count is:", count)
        count -= 1



The general structure of a :code:`while` loop is as follows

.. code-block:: python

    while #some condition is true:
        #execute the indented code

We can execute any code we want inside a while loop. We can check for traffic on a web server or check the price of Bitcoin. If we want to keep doing something forever, we can write the following code:

.. code-block:: python

    while True:
        buy_bitcoin_low()
        sell_bitcoin_high()

The preceding code will keep running until we tell it to stop. 

Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Write a `while` statement that will print every letter of the following string: "The airspeed velocity of an unladen swallow." 