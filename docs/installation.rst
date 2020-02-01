.. highlight:: shell

============
Installation
============


Stable release
--------------

To install Hydrodata, run this command in your terminal:

.. code-block:: console

    $ pip install hydrodata

Additionally, a `7z` decompressor is required for extracting the NHDPlus files. For more information please refer
to `pyunpack` `documentation`_.
This is the preferred method to install Hydrodata, as it will always install the most recent stable release.

If you don't have `pip`_ installed, this `Python installation guide`_ can guide
you through the process.

.. _documentation: https://pyunpack.readthedocs.io/en/latest
.. _pip: https://pip.pypa.io
.. _Python installation guide: http://docs.python-guide.org/en/latest/starting/installation/


From sources
------------

The sources for Hydrodata can be downloaded from the `Github repo`_.

You can either clone the public repository:

.. code-block:: console

    $ git clone git://github.com/cheginit/hydrodata

Or download the `tarball`_:

.. code-block:: console

    $ curl -OJL https://github.com/cheginit/hydrodata/tarball/master

Once you have a copy of the source, you can install it with:

.. code-block:: console

    $ python setup.py install


.. _Github repo: https://github.com/cheginit/hydrodata
.. _tarball: https://github.com/cheginit/hydrodata/tarball/master