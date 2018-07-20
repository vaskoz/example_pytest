# example_pytest
This is just a playground for setting up pytest

# Setup

```
> python3 -m virtualenv env
> source env/bin/activate
> pip install -r requirements.txt
```

# Run tests

I assume you're already in the virtualenv, but if you're not:

```
> source env/bin/activate
```

Now run all the tests by running `pytest` in the project root directory.
You should receive output like the following.

```
[example_pytest]> pytest
============================================= test session starts =============================================
platform darwin -- Python 3.7.0, pytest-3.6.3, py-1.5.4, pluggy-0.6.0
rootdir: /Users/vasko/code/example_pytest, inifile:
collected 1 item

tests/test_add.py .
```
