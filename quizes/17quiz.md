### What does 'batteries included' mean in Python?
- [ ] Python can be used to control IOT devices.
- [ ] Python has an extensive Standard Library. 
- [ ] Python is ideal for Raspberry Pi projects.
- [ ] None of the above.

### Which of the following is *not* true of the Python Standard Library?
- [ ] Python Standard Library modules and packages must be imported.
- [ ] You get the Standard Library when you install Python.
- [ ] The Standard Library is too advanced for beginners. 
- [ ] All of the above are true.


### What will print to the console after running the following Python code?

``` python
import random
print(random.randint(1,6))
```

- [ ] 6
- [ ] 5
- [ ] A random number between 1 and 6 inclusive.
- [ ] A random number between 1 and 6 exclusive.


### What will happen after running the following Python code?

``` python
import webbrowser
url = 'https://veroskills.com/'

webbrowser.open_new(url)
```

- [ ] The Veroskills website will open in the default browser.
- [ ] Nothing
- [ ] You will get an error if you don't install the Standard Library.
- [ ] None of the above.


### What will print to the console after running the following Python code?

``` python
import urllib.request, json

with urllib.request.urlopen("https://api.coindesk.com/v1/bpi/currentprice.json") as url:
    data = json.loads(url.read().decode())
    print(data['bpi']['USD']['rate'])
```
- [ ] It will print the current price of Bitcoin.
- [ ] This is not in the Python Standard Library.
- [ ] This module does not require an internet connection.
- [ ] Nothing will print.



