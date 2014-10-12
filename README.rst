Jansson-BB10 README
==============

.. image:: https://travis-ci.org/akheron/jansson.png
  :target: https://travis-ci.org/akheron/jansson

.. image:: https://ci.appveyor.com/api/projects/status/lmhkkc4q8cwc65ko
  :target: https://ci.appveyor.com/project/akheron/jansson

Jansson_ is a C library for encoding, decoding and manipulating JSON
data. Its main features and design principles are:

- Simple and intuitive API and data model

- Comprehensive documentation

- No dependencies on other libraries

- Full Unicode support (UTF-8)

- Extensive test suite

Jansson is licensed under the `MIT license`_; see LICENSE in the
source distribution for details.


Compilation and Installation for BlackBerry 10
----------------------------------------------------------

- Import project into Momentics IDE

- Build


Including Jansson in another BB10 Project
------------------------------------

- Import Jansson into workspace

- Right click on the project you want to use Jansson with

- Select Configure -> Add Library...

- Select "Library project in the workspace" and then "Next >"

- Select "public" by clicking the checkbox (public and jansson will be selected) and click "Finish"


In your project you can now use Jansson

   #include <jansson.h>

   
Documentation
-------------

Prebuilt HTML documentation is available at
http://www.digip.org/jansson/doc/.

The documentation source is in the ``doc/`` subdirectory. To generate
HTML documentation, invoke::

   $ make html

Then, point your browser to ``doc/_build/html/index.html``. Sphinx_
1.0 or newer is required to generate the documentation.


.. _Jansson: http://www.digip.org/jansson/
.. _`MIT license`: http://www.opensource.org/licenses/mit-license.php
.. _Sphinx: http://sphinx.pocoo.org/
