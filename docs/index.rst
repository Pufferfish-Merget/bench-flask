.. rst-class:: hide-header

Welcome to Flask
================

.. image:: _static/flask-horizontal.png
    :align: center

Welcome to Flask's documentation. Get started with :doc:`installation`
and then get an overview with the :doc:`quickstart`. There is also a
more detailed :doc:`tutorial/index` that shows how to create a small but
complete application with Flask. Common patterns are described in the
:doc:`patterns/index` section. The rest of the docs describe each
component of Flask in detail, with a full reference in the :doc:`api`
section.

Flask depends on the `Werkzeug`_ WSGI toolkit, the `Jinja`_ template engine, and the
`Click`_ CLI toolkit. Be sure to check their documentation as well as Flask's when
looking for information.

.. _Werkzeug: https://werkzeug.palletsprojects.com
.. _Jinja: https://jinja.palletsprojects.com
.. _Click: https://click.palletsprojects.com


User's Guide
------------

This part of the documentation, which is mostly prose, begins with some
background information about Flask, then focuses on step-by-step
instructions for web development with Flask.

.. toctree::
   :maxdepth: 2

   foreword
   advanced_foreword
   installation
   quickstart
   tutorial/index
   templating
   testing
   errorhandling
   debugging
   logging
   config
   signals
   views
   appcontext
   reqcontext
   blueprints
   extensions
   cli
   server
   shell
   patterns/index
   deploying/index
   becomingbig
   async-await


API Reference
-------------

If you are looking for information on a specific function, class or
method, this part of the documentation is for you.

.. toctree::
   :maxdepth: 2

   api


Additional Notes
----------------

Design notes, legal information and changelog are here for the interested.

.. toctree::
   :maxdepth: 2

   design
   htmlfaq
   security
   extensiondev
   contributing
   license
   changes
