### What does 'dunder' mean in Python?
- [ ] It is a Python keyword.
- [ ] It is a word for the magic methods in a Python class.
- [ ] It is a portmanteau of "double" and "underscore".
- [x] both b and c are correct.

### Which of the following is *not* true of the Python classes?
- [ ] Python classes are like blueprints for objects.
- [ ] Everything in Python is an object, so everything comes from a class.
- [x] Python only has builtin classes, you cannot make your own classes.
- [ ] All of the above are true.


### What will print to the console after running the following Python code?

``` python
    class Dog:
        def __init__(self, name, breed):
            self.name = name
            self.breed = breed
    fido = Dog("Fido")
    print(fido.name)
```

- [ ] "Fido"
- [ ] fido.name
- [ ] This will cause a warning, but the code will compile.
- [x] This will cause an error because a breed was not supplied.


### What will happen after running the following Python code?

``` python
    class Dog:
        def __init__(self, name, breed="lab"):
            self.name = name
            self.breed = breed
    fido = Dog("Fido")
    print(fido.name)
```

- [x] "Fido"
- [ ] fido.name
- [ ] This will cause a warning, but the code will compile.
- [ ] This will cause an error because a breed was not supplied.


### Which of the following is true of the code below?

``` python
    class MyClass:
        pass
```
- [ ] This code is not valid Python code.
- [ ] MyClass is a module in the Python Standard Library.
- [x] MyClass has several builtin dunder methods.
- [ ] The `pass` keyword cannot be used for classes.



