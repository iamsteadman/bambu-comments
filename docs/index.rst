Bambu Comments
==============

Generic model commenting

About Bambu Comments
--------------------

This package provides a secure, spam-aware, approval-based commenting
system for Django models. Used in conjunction with an Akismet API key,
it will keep spam from hitting inboxes, and works with other tools in
the Bambu toolset to provide notifications and perform other actions.

Comments are sanitised before being posted, so you don't need to run
them through a bunch of filters.

About Bambu Tools 2.0
---------------------

This is part of a toolset called Bambu Tools. It's being moved from a
namespace of ``bambu`` to its own 'root-level' package, along with all
the other tools in the set. If you're upgrading from a version prior to
2.0, please make sure to update your code to use ``bambu_comments`` rather
than ``bambu.comments``.

Installation
------------

Install the package via Pip:

::

    pip install bambu-comments

Add it to your ``INSTALLED_APPS`` list:

::

    INSTALLED_APPS = (
        ...
        'bambu_comments'
    )

Run ``manage.py syncdb`` or ``manage.py migrate`` to setup the database
tables.

Documentation
-------------

Full documentation can be found at
`ReadTheDocs <http://bambu-comments.readthedocs.org/>`_.

Questions or suggestions?
-------------------------

Find me on Twitter (@iamsteadman) or `visit my blog <http://steadman.io/>`_.

Contents
========

.. toctree::
   :maxdepth: 2
   
   settings
   haystack
   notifications

API reference
=============

.. toctree::
   :maxdepth: 2

   tags
   models

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
