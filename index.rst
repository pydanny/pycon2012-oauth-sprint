===================================================
Welcome to the PyCon 2012 OAuth Sprint page!
===================================================

We're going to make Python's OAuth story better!

* When: March 12 - 15, 2012
* Where: Santa Clara Hotel and around the world

Plan
======

#. Get Oauth 1.0a working well. After that's done, work on implementing against select OAuth 2 specifications.
#. Clean up existing OAuth consumers and providers.
#. Document everything.
#. Increase test coverage on everything.
#. Add a page to http://docs.python-guide.org that is the Python OAuth story.
#. Describe a specification for a high level of quality in an OAuth-based project. Those who meet this specification get their project listed on the forthcoming http://docs.python-guide.org page.

Communication
===============

* IRC channel: forthcoming
* Twitter hashtag: #pycon-oauth

Schedule
=========

Monday
------

OAuthlib_ and general cleanup

* Idan Gazit and a select group of others work to get OAuthlib_ to a state where consumer and provider authors can use this new library. 

    * .. warning:: I can't put up a wall around Idan, so I'm going to ask that people refrain from distracting him until OAuthlib is ready to go.

* Create OAuthlib_ documentation and tests. **I'll be putting up rules for pull requests for this shortly**.
    
* Authors of existing OAuth Consumer and Provider tools can:

    * close out existing bugs.
    * fix documentation.
    * increase test coverage.
    * Create turnkey example projects. 

* Describe the formal specification for getting projects into the forthcoming  http://docs.python-guide.org OAuth page.

.. _ OAuthlib: https://github.com/idangazit/oauthlib

Tuesday through Thursday
------------------------

OAuthlib should be ready to go. In which case:

* Authors of existing OAuth Consumer and Provider tools can migrate/port/branch their projects over to OAuthlib.

* Consumer and Provider example implementations for all Python frameworks:

    * Django
    * Flask
    * Pyramid
    * Web2py
    * Aspen.io
    * Cherrypy
    * Any that I've missed



Contents:

.. toctree::
   :maxdepth: 2



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

