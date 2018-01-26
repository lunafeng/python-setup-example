# python-setup-example
This repo is a small simple example showing you how to set up and install your own package.

Step 1:
Create `setup.py` at the top level of your package

Step 2:
Create `__init__.py` under each of the package you want to import

Step 3:
In your `setup.py`, modify `packages` array to include all the packages you want to import

Step 4:
Install package by running:
`python setup.py install`

It should install the pacakge and you can find it by:
`pip freeze`

Then you can import your packages anywhere in your system
