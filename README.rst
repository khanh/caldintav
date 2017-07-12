CALDINTAV-v3.0
=========================

Caldintav is a program for the dynamic calculation of railway bridges developed in Python language by the Computational Mechanics Group of the Technical University of Madrid, Spain.

The homepage of caldintav program with user documentation is located on:

http://www.mecanica.upm.es/

Getting the latest code
=========================

To get the ultimate version of the Caldintav program, you can visit our 
homepage: http://www.mecanica.upm.es

Installing
=========================

You can use `pip` to install joblib::

    pip install caldintav-3.0.tar.gz

from any directory or

    python setup.py sdist

from the source directory.

To run Caldintav program, some dependencies are needed:  Numpy, Sympy,
Scipy, Joblib anf GTK

Making a source tarball
=========================

To create a source tarball, eg for packaging or distributing, run the
following command::

    python setup.py sdist

The tarball will be created in the `dist` directory. This command will
compile the docs, and the resulting tarball can be installed with
no extra dependencies than the Python standard library. You will need
setuptool and sphinx.
