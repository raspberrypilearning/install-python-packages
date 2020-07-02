## Using your Python editors package installation tool

Online and dedicated editors usually come with "pre-installed packages" or have their own package installers which can be used to install additional packages.

You can find out more about online and dedicated editors in our [Python install options](https://projects.raspberrypi.org/en/projects/python-install-options) guidance.

Below is guidance regarding some of the popular online and installed Python editors. If your editor is not listed, be sure to check out their documentation.

### trinket.io

![trinket.io screenshot](images/trinket.png)

[trinket.io comes with some python modules pre-installed](https://trinket.io/docs/python) which you can use without having to install them yourself. 

There is no option to install additional packages if the module you wish to use is not available.

### repl.it

![repl.it screenshot](images/replit.png)

The [repl.it](https://repl.it) Packages feature can be used to add additional modules to your project. Due to the limitations of all online editors not all modules will work, however many will.

--- collapse ---

---
title: Install packages with repl.it
---

+ Open your program in repl.it.

+ Select the packages icon from the menu.

![Packages icon highlighted on the repl.it window](images/replit_step1.png)

+ Search for the name of the package e.g. `wikipedia` and click on the name of the package you wish to install.

![wikipedia has been entered into the search box and the wikipedia package is highlighted in the list of packages returned](images/replit_step2.png)

+ Click the **+** icon to download install the package.

![the + icon next to the wikipedia package is highlighted](images/replit_step3.png)

+ Installation progress will be shown in the terminal.

![the terminal showing the messages from the wikipedia package installation](images/replit_step4.png)

+ Installation is complete when the **+** icon stops spinning and is replaced by a **-**.

![the - icon next to the wikipedia package is highlighted](images/replit_step5.png)

**Note** - if you want to use a package in multiple programs, you will need to install it in each program.

--- /collapse ---

### Thonny

![thonny IDE screenshot](images/thonny.png)

[Thonny](https://thonny.org) includes a Package Manager which can be used to install packages from [PyPI](https://pypi.org). The majority of modules should be supported. 

--- collapse ---

---
title: Install packages with Thonny
---

**Note** - if you are using Thonny in *simple mode* you will need to click ***switch to regular mode*** amd restart Thonny to install packages. 

![thonny in simple mode with the "switch to regular mode" option in the top right highlighted](images/thonny_simple_mode.png)

+ Select **Manage Packages** from **tools** menu.

![thonny IDE with the Manage Packages option on the tools menu selected](images/thonny_step1.png)

+ Enter the name of the package you want to install (e.g. wikipedia) and click **Find package from PyPI**.

![thonny manage packages tool, wikipedia is entered into the text box and "find package from pypi" button are highlighted](images/thonny_step2.png)

+ Click **Install** to install the package.

![thonny manage packages tool, showing the wikipedia package, the install button is highlighted](images/thonny_step3.png)

+ The package will be downloaded and installed. A pop-up window will show the installation progress.
 
![thonny manage packages tool, the pop-up window shows the progress of installing the wikipedia package](images/thonny_step4.png)

+ When the package has been installed the pop-up window will close and you will have the option to uninstall the package.

![thonny manage packages tool showing the wikipedia package with the option to uninstall](images/thonny_step5.png)

--- /collapse ---

### Mu

![Mu IDE](images/mu.png)

The current release of [Mu](https://codewith.mu) contains a "pre-installed" set of common modules. You cannot install any additional packages. 

The [alpha release of Mu](https://codewith.mu/en/download) includes a tool for installing "Third Party Packages" from [PyPI](https://pypi.org). The majority of modules should be supported. 

--- collapse ---

---
title: Installing packages with Mu Alpha
---

+ Click on the Mu Administration **cog** in the bottom right.

![Mu admin button cog highlighted in the bottom right](images/mu_step1.png)

+ Select the **Third Party Packages** tab.

![Mu Administration, with the Third Party Packages tab highlighted](images/mu_step2.png)

+ Enter the name of the package you wish to install e.g. `wikipedia` and click **OK**.

![third party packages window with wikipedia entered](images/mu_step3.png)

+ The package will be collected (downloaded) and installed.  

![third party packages download and FINISHED message](images/mu_step5.png)

Multiple packages can be installed by placing the name of individual packages on new lines. Packages can be un-installed by removing the package name from the list and clicking **OK**.

--- /collapse ---