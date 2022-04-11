### Which of the following is the correct definition of a Python module?
- [x] A Python file.
- [ ] A Python package.
- [ ] A Python directory.
- [ ] A Python builtin method.



### Which of the following is *not* an true of modules in Python?
- [ ] Modules are a way of organizing Python code.
- [ ] Modules can be imported into other files
- [x] Modules are special types of python files.
- [ ] All of the above are true.


### What does the following Python code do in the file in which it is written?

``` python
import my_module
```

- [x] Nothing unless a file called my_module.py is defined in the same directory.
- [ ] It allows the file to use all functions and variables defined in the module.
- [ ] a and b are both true.
- [ ] None of the above.

### What is the difference between:

``` python
import my_module
```
and

``` python
from my_module import *
```

- [x] The first one requires a namespace while the second does not.
- [ ] The second one is not very Pythonic.
- [ ] They are equivalent ways of writing the same thing.
- [ ] The second method is easier to work with.


### If `my_module.py` has the following code: `name = "Daniel"`. What will print to the console when the Python code below runs. Assume `my_module.py` is in the same directory as the file containing the code below.

``` python
from my_module import name
print(name)
```
- [x] "Daniel"
- [ ] NameError
- [ ] name
- [ ] Nothing will print without a namespace.



