### Which of the following is the correct definition of a Python function?
- [x] A series of statements which returns some value to a caller.
- [ ] A Python data type that must return a value or `None`.
- [ ] Python does not have functions, it has methods.
- [ ] All of the above.

### Which of the following is the correct definition of scope in Python?
- [x] It is were a variable is visible.
- [ ] Python does not have block scope.
- [ ] Python uses LEGB to look for variables
- [ ] None of the above.


### What will print to the console after running the following Python code?

``` python
global_var = "global"
def func():
      global_var = "local"
func()
print(global_var)
```

- [ ] global
- [x] local
- [ ] global_var is out of scope.

### What will print to the console after running the following Python code?

``` python
global_var = "global"
def func():
      local_var = "local"
      print(global_var)
func()

```

- [x] global
- [ ] local
- [ ] global and local
- [ ] Nothing will print.


### What will print to the console after running the following Python code?

``` python

global_var = "global"
def func():
      local_var = "local"
      print(global_var, local_var)
func()

```
- [ ] global
- [ ] local
- [x] global and local
- [ ] Nothing will print.



