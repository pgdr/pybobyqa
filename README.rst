===================================================================================
Py-BOBYQA: Derivative-Free Solver for Bound-Constrained Minimization |PyPI Version|
===================================================================================
Py-BOBYQA is a flexible package for solving bound-constrained general objective minimization, without requiring derivatives of the objective. It is a Python implementation of the BOBYQA algorithm by Powell.

More details about Py-BOBYQA can be found in our paper: C. Cartis, J. Fiala, B. Marteau and L. Roberts, Improving the Flexibility and Robustness of Model-Based Derivative-Free Optimization Solvers, technical report, University of Oxford, (2018).

The original paper by Powell is: M. J. D. Powell, The BOBYQA algorithm for bound constrained optimization without derivatives, technical report DAMTP 2009/NA06, University of Cambridge (2009), and the original Fortran implementation is available `here <http://mat.uc.pt/~zhang/software.html>`_.

Documentation
-------------
See manual.pdf or `here <http://people.maths.ox.ac.uk/robertsl/pybobyqa>`_.

Requirements
------------
Py-BOBYQA requires the following software to be installed:

* Python 2.7 or Python 3 (http://www.python.org/)

Additionally, the following python packages should be installed (these will be installed automatically if using *pip*, see `Installation using pip`_):

* NumPy 1.11 or higher (http://www.numpy.org/)
* SciPy 0.18 or higher (http://www.scipy.org/)
* Pandas 0.17 or higher (http://pandas.pydata.org/)

Installation using pip
----------------------
For easy installation, use *pip* (http://www.pip-installer.org/) as root::

    $ [sudo] pip install Py-BOBYQA

or alternatively *easy_install*::

    $ [sudo] easy_install Py-BOBYQA

If you do not have root privileges or you want to install Py-BOBYQA for your private use, you can use::

    $ pip install --user Py-BOBYQA

which will install Py-BOBYQA in your home directory.

Note that if an older install of Py-BOBYQA is present on your system you can use::

    $ [sudo] pip install --upgrade Py-BOBYQA

to upgrade Py-BOBYQA to the latest version.

Manual installation
-------------------
Alternatively, you can download the source code from `Github <https://github.com/numericalalgorithmsgroup/pybobyqa>`_ and unpack as follows:

 .. code-block:: bash

    $ git clone https://github.com/numericalalgorithmsgroup/pybobyqa
    $ cd pybobyqa

Py-BOBYQA is written in pure Python and requires no compilation. It can be installed using:

 .. code-block:: bash

    $ [sudo] pip install .

If you do not have root privileges or you want to install Py-BOBYQA for your private use, you can use:

 .. code-block:: bash

    $ pip install --user .

instead.

Testing
-------
If you installed Py-BOBYQA manually, you can test your installation by running:

 .. code-block:: bash

    $ python setup.py test

Alternatively, the HTML documentation provides some simple examples of how to run Py-BOBYQA.

Examples
--------
Examples of how to run Py-BOBYQA are given in the `documentation <http://people.maths.ox.ac.uk/robertsl/pybobyqa>`_, and the `examples <https://github.com/numericalalgorithmsgroup/pybobyqa/tree/master/examples>`_ directory in Github.

Uninstallation
--------------
If Py-BOBYQA was installed using *pip* you can uninstall as follows:

 .. code-block:: bash

    $ [sudo] pip uninstall Py-BOBYQA

If Py-BOBYQA was installed manually you have to remove the installed files by hand (located in your python site-packages directory).

Bugs
----
Please report any bugs using GitHub's issue tracker.

License
-------
This algorithm is released under the GNU GPL license.

.. |PyPI Version| image:: https://img.shields.io/pypi/v/Py-BOBYQA.svg
                  :target: https://pypi.python.org/pypi/Py-BOBYQA
