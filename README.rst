* This README serves two purposes: description of setup-with-teeth, and a template for your own README.
* Rewrite this README to be relevant to your package, then remove these lines

==============================================================
setup-with-teeth: setup.py & file hierarchy for fast packaging
==============================================================

As long as you follow the file hierarchy and a few other conventions, this
allows for packaging python libraries with minimal developer-time.


Features
--------

* DRY principle throughout, including macro-expansions in files based on
  settings

* Auto adding of new lib files to package

* Defaults to FHS-friendly layout


Installation
------------

It would obviously be silly to "package" this. It is a packaging skeleton
itself. Just:

1. Clone this repository (or expand this archive).

2. Edit settings in setup.py

3. Edit and add files to your liking

4. Remove this README.rst file

5. If you cloned this from a repo remove the versioning files (e.g. ".git"
   directory for git).

6. Initialise your versioning system inside this directory.


Build Status
------------

When properly integrated with Travis the project's status
should appear below this:

.. image:: https://secure.travis-ci.org/XXXXXXX/XXXXXXX.png?branch=master
   :alt: Build Status
   :target: https://secure.travis-ci.org/XXXXXXX/XXXXXXX


Authors
-------

Rowan Thorpe <rowan@rowanthorpe.com>


License
-------

setup-with-teeth uses the MIT license, check LICENSE file.


Contributors
------------

* Just Rowan Thorpe, so far...


Thanks also to
--------------

* TODO
