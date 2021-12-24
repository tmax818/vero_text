Classes: Part 2
===============

Python classes are the heart and soul of the Python programming language. It is a very complex topic and we have only given you a taste of what's to come. Object oriented programming is very difficult for the new programmer to understand. If it's not clear at this point, you are normal! OOP in general, and pointers in C are two topics that **everyone** struggles with! Give yourself permission to not understand this at first. 

However, it is not impossible to grasp. Practice as much as you can building classes and creating objects from them. One day, it will *click*, I promise.

Try the following code:

.. code-block:: python

    class MyClass
        def __init__(self):
            print(self)

    c = MyClass()

What happens? What is printed to the screen? This exercise will help you understand what ``self`` is in an object. You should see something like this:

.. code-block:: python

    <__main__.MyClass object at 0x7f98a3ad6340>

This is how Python represents the object that is created from the ``MyClass`` class. The number, 0x7f98a3ad6340, is a hexadecimal number that represents the memory location in my computer where the object is stored. The number you get will be different. This shows the relationship between a class and the object created from the class. When you write your class, you can access the object that will be created from the class with the ``self`` keyword. 


Exercise
++++++++

.. admonition:: Practice these in the Veroskills interface

   - Read the documentation for Python classes. Don't just read, code along! Write out the examples and run the code.
   - Write simple classes and try to call the dunder methods that are builtin to them.



Further Reading
+++++++++++++++

- `Python classes <https://docs.python.org/3/tutorial/classes.html>`_ 