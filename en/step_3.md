## Using your Python editor's package installation tool

Online and dedicated Python editors usually come with pre-installed packages, or have their own package installers, which you can use to install the packages you need.

You can find out more about online and dedicated editors in our guidance about [applications for creating Python programs](https://projects.raspberrypi.org/en/projects/python-install-options).

Below you'll find how-to guides related to some popular online and installed Python editors; if your editor is not listed, be sure to check out its documentation.

### trinket.io

![trinket.io screenshot](images/trinket.png)

[The online IDE on trinket.io](https://trinket.io/docs/python) comes with some pre-installed Python modules, which you can use straight away. 

Trinket doesn't provide an option to install other packages if the module you wish to use is not available.

### repl.it

![repl.it screenshot](images/replit.png)

On [repl.it](https://repl.it), you can use the Packages feature to add Python modules to your project.

Due to the limitations of all online editors, you'll be able to add some but not all modules.

--- collapse ---

---
title: Install packages with repl.it
---

+ Open your Python program in repl.it.

+ Click on the **Packages** icon in the menu.

![Packages icon highlighted on the repl.it window](images/replit_step1.png)

+ Search for the name of the package you wish to install, e.g. `wikipedia`. Click on the name of the package in the search results.

![wikipedia has been entered into the search box and the wikipedia package is highlighted in the list of packages returned](images/replit_step2.png)

+ Click the **+** icon to install the package.

![the + icon next to the wikipedia package is highlighted](images/replit_step3.png)

+ Installation progress will be shown in the terminal.

![the terminal showing the messages from the wikipedia package installation](images/replit_step4.png)

+ Installation is complete when the **+** icon stops spinning and is replaced by a **-**.

![the - icon next to the wikipedia package is highlighted](images/replit_step5.png)

**Note**: If you want to use a package in multiple programs on repl.it, you need to install it for each program individually.

--- /collapse ---

### Thonny

![thonny IDE screenshot](images/thonny.png)

[Thonny](https://thonny.org) includes a Package Manager, which you can use to install packages from [PyPI](https://pypi.org). Thonny supports the majority of Python modules. 

--- collapse ---

---
title: Install packages with Thonny
---

**Note**: If you are using Thonny in simple mode, then to install packages, you need to first click on **switch to regular mode** and then restart Thonny. 

![thonny in simple mode with the "switch to regular mode" option in the top right highlighted](images/thonny_simple_mode.png)

+ Select **Manage Packages** from the **tools** menu.

![thonny IDE with the Manage Packages option on the tools menu selected](images/thonny_step1.png)

+ Enter the name of the package you want to install (e.g. `wikipedia`), and then click on **Find package from PyPI**.

![thonny manage packages tool, wikipedia is entered into the text box and "find package from pypi" button are highlighted](images/thonny_step2.png)

+ Click on **Install** to install the package.

![thonny manage packages tool, showing the wikipedia package, the install button is highlighted](images/thonny_step3.png)

+ The package will be downloaded and installed. A pop-up window will show the installation progress.
 
![thonny manage packages tool, the pop-up window shows the progress of installing the wikipedia package](images/thonny_step4.png)

+ When the package has been installed, the pop-up window will close, and you will have the option to uninstall the package.

![thonny manage packages tool showing the wikipedia package with the option to uninstall](images/thonny_step5.png)

--- /collapse ---

### Mu

![Mu IDE](images/mu.png)

The [current stable version of Mu](https://codewith.mu) contains a pre-installed set of commonly used Python modules. You cannot install any additional packages with it. 

The [alpha release of the next version of Mu (Mu Alpha)](https://codewith.mu/en/download) includes a tool for installing third-party packages from [PyPI](https://pypi.org). This version of Mu should support the majority of Python modules. 

--- collapse ---

---
title: Installing packages with Mu Alpha
---

+ Click on the Mu Administration **cog** in the bottom right-hand corner.

![Mu admin button cog highlighted in the bottom right](images/mu_step1.png)

+ Select the **Third Party Packages** tab.

![Mu Administration, with the Third Party Packages tab highlighted](images/mu_step2.png)

+ Enter the name of the package you want to install, e.g. `wikipedia`, and then click on **OK**.

![third party packages window with wikipedia entered](images/mu_step3.png)

+ The package will be collected (i.e. downloaded) and installed.  

![third party packages download and FINISHED message](images/mu_step5.png)

You can install multiple packages quickly by adding the names of the individual packages on new lines.

To un-install a package, remove the package's name from the list, and then click **OK**.

--- /collapse ---
