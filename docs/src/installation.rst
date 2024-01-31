.. _installation:

############
Installation
############

.. _installation_googlecolab:

============
Google Colab
============

Using :ref:`Google Colab <https://colab.google>` is the easiest way to get started.
Just add in the first cell of your notebook:

.. code-block:: python

    # Download and install latest version of the package
    !pip install --upgrade git+https://github.com/jparisu/sIArena.git

    # Or to download a specific version
    !pip install --upgrade git+https://github.com/jparisu/sIArena.git@v0.1

This will install the specific version of the package and make it available in the rest of the cells of your notebook.


===========================
Install in Windows Anaconda
===========================

In order to install the package in Windows Anaconda, the steps are the same as for :ref:`installation_googlecolab`.
The only detail is that ``git`` may not be installed by default in Anaconda.

From a command prompt, you can install it in a ``conda`` environment inside Anaconda:

.. code-block:: bash

    conda install git
    pip install --upgrade git+https://github.com/jparisu/sIArena.git@v0.1


===========
Coming soon
===========

- Installation from source
- Installation via ``pip``
- Installation via ``conda``
