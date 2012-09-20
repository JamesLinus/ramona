.. Ramona documentation master file, created by
   sphinx-quickstart on Sat Sep 15 19:55:30 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Ramona Documentation
====================

Ramona is an enterprise-grade **runtime supervisor** that allows controlling and monitoring software programs during their execution life cycle.

It provides supervisor/console functionality of init.d-like start/stop control, continuous integration (e.g. unit/functional/performance test launcher), deployment automation and other command-line oriented features. It is design the way that you should be able to extend that easily if needed (e.g. to include your own commands or tasks).

It is implemented in Python but it is not limited to be used only in Python projects.

Target platforms are all modern UNIXes, BSD derivates and Windows.

Project homepage: http://ateska.github.com/ramona

Contents:

.. toctree::
   :maxdepth: 2

   intro.rst
   install.rst
   features.rst
   quickref.rst
   credits.rst

.. [TODO]: Example of init.d script (and modern alternatives like init) for ramona-based app


Indices and tables
==================

* :ref:`genindex`
* :ref:`search`

.. * :ref:`modindex`