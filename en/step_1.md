## What is a Python package?

A Python package is a container for a module or collection of modules that allow your program to do predefined things. Modules are created and made publicly available by organisations, teams, or individuals. Most packages are made available on the [Python Package Index (PyPI)](https://pypi.org).

You are using a module every time you use an `import` statement in your program. For example:

```python
from time import sleep
import numpy as np
import pygame
```

Before you can use a Python module in your programs, you need to install its package. The only exception are modules in [the Python Standard Library](https://docs.python.org/3/library/), which is a collection of modules (e.g. `time`, `random`, `os`) that are **built into** Python and therefore do not need to be installed. The number in-built modules in the Standard Library is far, far smaller than the number of additional modules you can install via packages.

### How do I install a Python package?

Whether you can install a package depends on:

- How you are using Python on your computer
- Whether and how you installed Python
- Your level of access to change your computer's setup

You may wish to review our guidance about [different applications for creating Python programs](https://projects.raspberrypi.org/en/projects/python-install-options) for more information on how the application you choose influences whether you can install Python packages. Note that you cannot install all Python packages for use with an online IDE.

This guide provides guidance and advice on how to install Python packages depending on which application you use to write your programs. However, not all options can be addressed here, and your specific setup may affect your ability to install or use a specific Python package.

All Raspberry Pi Foundation projects, courses, and resources that involve Python coding describe which packages you need in order to complete the activities described, as well as any known issues or limitations.
