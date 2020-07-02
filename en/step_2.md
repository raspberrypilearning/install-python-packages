## Installing packages

The most common methods for installing packages are to use:

+ the tool provided with your Python editor
+ the `pip` / `pip3` command line utility which is included with a full Python install
+ an operating system specific installer provided by the package creators, such as a windows installer or debian apt package 

The choice of which to use is dependant on the specific setup of your computer but the following guidelines should help you make a decision:

1. If your Python editor has a **package installation tool**, it is recommended that you use it to install modules. 

    Note - using the package installation tool maybe the only way to install modules for use in your editor. Modules installed using the editor are also normally only be available to use within the editor.

2. If you are using a Raspberry Pi computer with the Raspberry Pi OS (Raspbian), it is recommended you [install packages with the pip3 command line utility](https://projects.raspberrypi.org/en/projects/install-python-packages/3).

3. If you have installed a full Python installation (from [python.org](https://python.org)) and are using either the default IDLE editor or a another standalone IDE, it is recommended you [use the pip3 command line utility](https://projects.raspberrypi.org/en/projects/install-python-packages/3).

4. If a package is not available on [PyPI](https://pypi.org), you should refer to the module’s install instructions for more information. Operating System specific installers may be available, or you may be able to install the module using the source code (advanced).

