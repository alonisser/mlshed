mlshed
####
.. .. |PyPI-Status| |PyPI-Versions| |Build-Status| |Codecov| |LICENCE|

Simple local/remote model store for Python.

.. |mlshed_icon| image:: https://github.com/shaypal5/mlshed/blob/cc5595bbb78f784a3174a07157083f755fc93172/mlshed.png
   :height: 87
   :width: 40 px
   :scale: 50 %
   
.. .. image:: https://github.com/shaypal5/mlshed/blob/b10a19a28cb1fc41d0c596df5bcd8390e7c22ee7/mlshed.png

.. code-block:: python

  from mlshed import Model

.. contents::

.. section-numbering::


Installation
============

.. code-block:: bash

  pip install mlshed


Features
========

* Pure python.
* Supports Python 3.5+.


Use
===

TBA


Contributing
============

Package author and current maintainer is Shay Palachy (shay.palachy@gmail.com); You are more than welcome to approach him for help. Contributions are very welcomed.

Installing for development
----------------------------

Clone:

.. code-block:: bash

  git clone git@github.com:shaypal5/mlshed.git


Install in development mode, including test dependencies:

.. code-block:: bash

  cd mlshed
  pip install -e '.[test]'


Running the tests
-----------------

To run the tests use:

.. code-block:: bash

  cd mlshed
  pytest


Adding documentation
--------------------

The project is documented using the `numpy docstring conventions`_, which were chosen as they are perhaps the most widely-spread conventions that are both supported by common tools such as Sphinx and result in human-readable docstrings. When documenting code you add to this project, follow `these conventions`_.

.. _`numpy docstring conventions`: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt
.. _`these conventions`: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt

Additionally, if you update this ``README.rst`` file,  use ``python setup.py checkdocs`` to validate it compiles.


Credits
=======

Created by `Shay Palachy <http://www.shaypalachy.com/>`_ (shay.palachy@gmail.com).


.. |PyPI-Status| image:: https://img.shields.io/pypi/v/mlshed.svg
  :target: https://pypi.python.org/pypi/mlshed

.. |PyPI-Versions| image:: https://img.shields.io/pypi/pyversions/mlshed.svg
   :target: https://pypi.python.org/pypi/mlshed

.. |Build-Status| image:: https://travis-ci.org/shaypal5/mlshed.svg?branch=master
  :target: https://travis-ci.org/shaypal5/mlshed

.. |LICENCE| image:: https://img.shields.io/github/license/shaypal5/mlshed.svg
  :target: https://github.com/shaypal5/mlshed/blob/master/LICENSE

.. |Codecov| image:: https://codecov.io/github/shaypal5/mlshed/coverage.svg?branch=master
   :target: https://codecov.io/github/shaypal5/mlshed?branch=master
