===================================================
Welcome to the PyCon 2012 OAuth Sprint page!
===================================================

We're going to make Python's OAuth story better!

* When: March 12 - 15, 2012
* Where: Santa Clara Hotel and around the world
* IRC channel: pycon-oauth
* Twitter hashtag: #pycon-oauth

Plan
======

#. Get Oauth 1.0a working well. After that's done, work on implementing against select OAuth 2 specifications.
#. Clean up existing OAuth consumers and providers.
#. Document everything.
#. Increase test coverage on everything.
#. Add a page to http://docs.python-guide.org that is the Python OAuth story.
#. Describe a specification for a high level of quality in an OAuth-based project. Those who meet this specification get their project listed on the forthcoming http://docs.python-guide.org page.

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

* Describe the rules necessary for registering an example implementations on the forthcoming  http://docs.python-guide.org OAuth page.

.. _OAuthlib: https://github.com/idangazit/oauthlib

Tuesday through Thursday
------------------------

OAuthlib should be ready to go. In which case:

* Authors of existing OAuth Consumer and Provider tools can migrate/port/branch their projects over to OAuthlib.

* Rules forthcoming for getting these listed on the guide page, but we will need Consumer and Provider example implementations against OAuthlib for all Python frameworks:

    * Django
    * Flask
    * Pyramid
    * Web2py
    * Aspen.io
    * Cherrypy
    * Any that I've missed

General Coding/Documentation Notes
==========================================

It's going to take a little bit of time to get the formal rules up so here's a rough list of what we want:

* **Security is hard**. So write the simplest, cleanest, most documented code you can. Take your time and get it right, not just done.
* Unittest: Even though it can be tricky to test all pieces, get as many tests in as possible. Don't just try to get up your code coverage numbers either, actually test the code.
* Doctest: Again, tricky to do, but this is a great usecase for doctests.  Your doctests will serve as working documentation for people examining your code. If your doctests fail for someone that means your doctests 
