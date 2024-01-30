# zenity_py - Zenity for Python
Exactly what it says it is.

# How to install
Just type ```python3 -m pip install zeni_py``` and it should install just fine.

# How to use
In a python file, type
```python
from zenity import Zenity

# Zenity syntax - title, body, type, options[]
# the ! in !timeout means it is an option, not a value
z = Zenity("Title", "Body", "info", ["!timeout", 5])
```

This should create a new Zenity instance. Of course, this is an example, so you can change anything.
After that, add
```python
z.Open()
```

This should start up Zenity with the parameters you specified.
If a zenity window doesn't appear, something went wrong.
You can always print() the z variable, as the Zenity class returns the output.