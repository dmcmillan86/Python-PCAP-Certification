# Importing and Using Modules in Python

# Importing Modules

Modules allow for code to be divided into self-contained blocks
 - Independence
 - Maintainability
 - Resuability

To use a module it must first be 'installed'
Installed in one of three locations:
  - The local Directory - .py
  - A PYTHONPATH Directory - Env
  - One of the internal (sys.path) Directories - Global

# Using Import and Modules

Modules define their own 'namespace'
Namespace: a logical boundary in code where specific identifiers (names) are created and accessible
Import can import an entire module or pieces of a module and can redefine the namespace name
Use the 'as' alias to make calling a module easier and code cleaner 

# Installing Packages with Pip

Pip is the tool for installing 3rd party modules and packages from PyPi

currently over 300,000 projects on PyPi
Pip can be used to install packages from different libraries other than PyPi
This installs specific packages and all of it's dependencies
Can install to global location or virtual environments

Site-packages folder

you can use a txt file to install modules and packages by creating txt file, adding dependencies then calling in terminal: pip install -r filename.txt

Pipenv is a package to setup a virtual environment 
Pipenv lock creates a pipfile.lock in place can be installed anywhere else

# Writing Modules

Turn your own code into modules if: static code, complex code, or reusable code
if you got a .py file you have a module you can import. 
first place it looks for a module is in the local directory




