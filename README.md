# pypkg

# create own pkg

```
pip install git+https://github.com/kode2go/pypkg.git
```

```
Building wheels for collected packages: pypkg
  Building wheel for pypkg (setup.py) ... done
  Created wheel for pypkg: filename=pypkg-0.1-py3-none-any.whl size=1400 sha256=112249149af648e3a2e636c545ad30dc9506ff0e78650b4752764346d5599339
  Stored in directory: C:\Users\x\AppData\Local\Temp\pip-ephem-wheel-cache-3oxjcimm\wheels\31\2d\60\d5816cfc6ef1d20c8bc62d66fd9f51988e490cbeccb2594fff
Successfully built pypkg
Installing collected packages: pypkg
Successfully installed pypkg-0.1
```

```
$ python
Python 3.9.0 (default, Nov 15 2020, 08:30:55) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> import pypkg
>>> from pypkg.math_functions import add_numbers           
>>> result = add_numbers(5, 3)
>>> result
8
>>>
```
