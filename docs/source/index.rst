.. MatFeaLib documentation master file, created by
   sphinx-quickstart on Mon Mar 18 21:25:58 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. Welcome to MatFeaLib's documentation!
.. =====================================



.. image:: ./_static/MatFeaLib-logo-04.png
   :width: 903 px
   :alt: MatFeaLib
   :align: center

|

MatFeaLib
============


**MatFeaLib** (**Mat**\erials **Fea**\ture **Lib**\rary) is a Python library for generating elemental features from materials composition. These representations are often called “descriptors” and they can be used in machine learning and data analysis in the field of Materials Science. To get started you can check the basic tutorial.


.. note::

   This project is under active development.


MatFeaLib capable of fetching atomic features for a given single compound, list of compounds and aslo datasets in the form of pandas dataframe format.

It can present atomic features based on the initial values of avalable atomic species in the compound or statistical measures for any given inputed materials.

MatFeaLib currently incluce the following atomic feature collections:

.. list-table::
   :widths: 80 10
   :header-rows: 1

   * - Feature Collection
     - Features
   * - Mendeleev
     - ✓
   * - Matminer
     - ✓
   * - Pymatgen
     - ✓

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
