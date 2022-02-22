.. _install:

Installation of Py-DL
======================

This guide assumes you already have python and pip installed.

To install Py-DL, run the following command in your terminal::

    $ pip install Py-DL

Get the Source Code
-------------------

Py-DL is actively developed on GitHub, where the source is `available <https://github.com/Py-DL/pytube>`_.

You can either clone the public repository::

    $ git clone git://github.com/Py-DL/Py-DL.git

Or, download the `tarball <https://github.com/Py-DL/Py-DL/tarball/master>`_::

    $ curl -OL https://github.com/Py-DL/Py-DL/tarball/master
    # optionally, zipball is also available (for Windows users).

Once you have a copy of the source, you can embed it in your Python package, or install it into your site-packages by running::

    $ cd Py-DL
    $ python -m pip install .
