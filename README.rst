.. These are examples of badges you might want to add to your README:
   please update the URLs accordingly

    .. image:: https://api.cirrus-ci.com/github/<USER>/tabr.svg?branch=main
        :alt: Built Status
        :target: https://cirrus-ci.com/github/<USER>/tabr
    .. image:: https://readthedocs.org/projects/tabr/badge/?version=latest
        :alt: ReadTheDocs
        :target: https://tabr.readthedocs.io/en/stable/
    .. image:: https://img.shields.io/coveralls/github/<USER>/tabr/main.svg
        :alt: Coveralls
        :target: https://coveralls.io/r/<USER>/tabr
    .. image:: https://img.shields.io/pypi/v/tabr.svg
        :alt: PyPI-Server
        :target: https://pypi.org/project/tabr/
    .. image:: https://img.shields.io/conda/vn/conda-forge/tabr.svg
        :alt: Conda-Forge
        :target: https://anaconda.org/conda-forge/tabr
    .. image:: https://pepy.tech/badge/tabr/month
        :alt: Monthly Downloads
        :target: https://pepy.tech/project/tabr
    .. image:: https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter
        :alt: Twitter
        :target: https://twitter.com/tabr

.. image:: https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold
    :alt: Project generated with PyScaffold
    :target: https://pyscaffold.org/

|

====
tabr
====


    Add tabs to PDFs


I don't know about you, but when I read a book or journal article,
I like to use post-it notes and other sticky tabs to mark important 
text and make comments to myself. The `tabr` project provides an
API for doing the electronic equivalent of tabbing a book or 
document.


.. _pyscaffold-notes:

Making Changes & Contributing
=============================

A `conda`_ `environment.yml` file is provided to help get going
quickly, including installation of `pre-commit`_::

    $ conda env create -f environment.yml
    $ conda activate tabr
    $ pip install -e .

It is a good idea to update the hooks to the latest version::

    $ pre-commit autoupdate

.. _pre-commit: https://pre-commit.com/
.. _conda: https://conda.io

Note
====

This project has been set up using PyScaffold 4.3.1. For details and usage
information on PyScaffold see https://pyscaffold.org/.
