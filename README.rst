.. -*- mode: rst -*-

atlas
======

Brain atlas ROIs and query tools

.. image:: https://secure.travis-ci.org/neurita/atlas.png?branch=master
    :target: https://travis-ci.org/neurita/atlas

.. image:: https://coveralls.io/repos/neurita/atlas/badge.png
    :target: https://coveralls.io/r/neurita/atlas


Dependencies
============

Please see the requirements.txt and pip_requirements.txt files.

Install
=======

This package uses setuptools and Makefiles. 

I've made a workaround to deal with build dependencies of some requirements.
So there are two requirements files: requirements.txt and pip-requirements.txt.
The requirements.txt dependencies must be installed one by one, with::

    make install_deps

The following command will install everything with all dependencies::

    make install
    
If you already have the dependencies listed in requirements.txt installed, 
to install in your home directory, use::

    python setup.py install --user

To install for all users on Unix/Linux::

    python setup.py build
    sudo python setup.py install

You can also install it in development mode with::

    make develop


Development
===========

Code
----

Github
~~~~~~

You can check the latest sources with the command::

    git clone https://www.github.com/neurita/atlas.git

or if you have write privileges::

    git clone git@github.com:neurita/atlas.git

If you are going to create patches for this project, create a branch for it 
from the master branch.

The stable releases are tagged in the repository.


Testing
-------

TODO
