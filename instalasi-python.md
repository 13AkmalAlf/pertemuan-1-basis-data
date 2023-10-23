![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/dacb02ec-6abc-41ff-b7eb-65e803be04f6)how to install python.

1. Go to the official Python download page for Windows.

2. Find a stable Python 3 release. This tutorial was tested with Python version 3.12.0.

3. Click the appropriate link for your system to download the executable file: Windows installer (64-bit) or Windows installer (32-bit).

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/64d60f33-f073-4728-a0f4-9980c24cc8ca)

step 2-

1. After the installer is downloaded, double-click the .exe file, for example python-3.12.0-amd64.exe, to run the Python installer.

2. Select the Install launcher for all users checkbox, which enables all users of the computer to access the Python launcher application.

3. Select the Add python.exe to PATH checkbox, which enables users to launch Python from the command line.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/dc7918b6-c124-4675-ae01-14c6fee83fa5)

4. If you’re just getting started with Python and you want to install it with default features as described in the dialog, then click Install Now and go to Step 4 - Verify the Python Installation. To install other optional and advanced features, click Customize installation and continue.

5. The Optional Features include common tools and resources for Python and you can install all of them, even if you don’t plan to use them.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/2dd80e60-6f13-479b-a07a-b6dd9f3f4dab)

Select some or all of the following options:

Documentation: recommended
pip: recommended if you want to install other Python packages, such as NumPy or pandas
tcl/tk and IDLE: recommended if you plan to use IDLE or follow tutorials that use it
Python test suite: recommended for testing and learning
py launcher and for all users: recommended to enable users to launch Python from the command line

6. Click Next.

7. The Advanced Options dialog displays.

Python Advanced Options

Select the options that suit your requirements:

-Install for all users: recommended if you’re not the only user on this computer
-Associate files with Python: recommended, because this option associates all the Python file types with the launcher or editor
-Create shortcuts for installed applications: recommended to enable shortcuts for Python applications
-Add Python to environment variables: recommended to enable launching Python
-Precompile standard library: not required, it might down the installation
-Download debugging symbols and Download debug binaries: recommended only if you plan to create C or C++ extensions

Make note of the Python installation directory in case you need to reference it later.

8. Click Install to start the installation.

9. After the installation is complete, a Setup was successful message displays.

Python setup was successful

Step 3-

Adding Python to the Environment Variables (optional)

Skip this step if you selected Add Python to environment variables during installation.

If you want to access Python through the command line but you didn’t add Python to your environment variables during installation, then you can still do it manually.

Before you start, locate the Python installation directory on your system. The following directories are examples of the default directory paths:

-C:\Program Files\Python310: if you selected Install for all users during installation, then the directory will be system wide
-C:\Users\Sammy\AppData\Local\Programs\Python\Python310: if you didn’t select Install for all users during installation, then the directory will be in the Windows user path
Note that the folder name will be different if you installed a different version, but will still start with Python.

1. Go to Start and enter advanced system settings in the search bar.

2. Click View advanced system settings.

3. In the System Properties dialog, click the Advanced tab and then click Environment Variables.

4. Depending on your installation:

-If you selected Install for all users during installation, select Path from the list of System Variables and click Edit.
-If you didn’t select Install for all users during installation, select Path from the list of User Variables and click Edit.

5. Click New and enter the Python directory path, then click OK until all the dialogs are closed.

Step 4-

Verify the Python Installation

You can verify whether the Python installation is successful either through the command line or through the Integrated Development Environment (IDLE) application, if you chose to install it.

Go to Start and enter cmd in the search bar. Click Command Prompt.

Enter the following command in the command prompt:

          python --version

An example of the output is:

Output

          python 3.12.0

You can also check the version of Python by opening the IDLE application. Go to Start and enter python in the search bar and then click the IDLE app, for example IDLE (Python 3.10 64-bit).

Verify if Python is installed using IDLE app

You can start coding in Python using IDLE or your preferred code editor.
