# python-setup-example
This repo is a small simple example showing you how to set up and install your own package.

Step 1:
Create `setup.py` at the top level of your package

Step 2:
Create `__init__.py` under each of the package you want to import

Step 3:
In your `setup.py`, modify `packages` array to include all the packages you want to import
You can also define your package name and versions etc. You can find details here: http://setuptools.readthedocs.io/en/latest/setuptools.html

Step 4:
Install package by running:
`python setup.py install`

It will generate two folders named `build` and `YOUR_PACKAGE_NAME.egg-info` and install the pacakge.
You can find your installed pacakges by:
`pip freeze`

Now, you can import your packages anywhere in your system
