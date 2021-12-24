Classes: Part 1
===============

The following is the most basic Python class you can write:

.. code-block:: python

    class MyClass:
        pass
    c = MyClass()

The :code:`dir()` function will show all the methods available on an object. Running :code:`print(dir(c))` will give the following:

.. code-block:: bash

    ['__class__', '__delattr__', '__dict__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__le__', '__lt__', '__module__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', '__weakref__']

We did not define any of these methods. These are methods that we have access to simply because our object created from a Python class. Classes are a powerful way to bundle attributes and methods. The classes we write in our programs can be thought of as analogous to real world things. 

If we are creating a space adventure game, our program will have things like spaceships, planets, stars and the like. The spaceship in our game will have attributes and methods. The following might be a way to code our spaceship using Python:


.. code-block:: python

    class Spaceship:

        def __init__(self, model, position, damage=0):
            self.model = model
            self.position = position
            self.damage = damage

        def fire_cannon(self):
            print("The cannon has fired.")

The properties or attributes for our spaceship are: model, position, and damage. In this simple example, our spaceship only has one method, ``fire_cannon``. This is a convenient way to keep track of all the things our spaceship *has* and *can do*. The things our spaceship *has* are its attributes. The things our *can do* are its methods.

When our game starts, we simply create a spaceship object:

.. code-block:: python

    space_ship = Spaceship("XP-39", (0,0))

This gives us a spaceship object, ``space_ship`` that can then interact with other objects in our game. When the ``space_ship`` is destroyed in the game, we simply make another one from our ``Spaceship`` class.


Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Practice writing Python classes.
   - Write your own game using Python classes. Decide how your objects will interact. Start by having the game play take place in the console.



Further Reading
+++++++++++++++

- `Python classes <https://docs.python.org/3/tutorial/classes.html>`_ 