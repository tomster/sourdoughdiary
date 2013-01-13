This is the repository to build the sourdoughdiary blog.

Installing the requirements
===========================

Check out a copy of this repository. Make sure the name of the remote is origin (which is the default):

    git clone git@github.com:tomster/sourdoughdiary
    cd sourdoughdiary

Create a virtual environment and install the dependencies like so::

    virtualenv .
    source bin/activate
    pip install pelican ghp-import

Create an entry
===============

Simply add files inside ``content/``, using the restructured text format.


Publishing
==========

First rebuild the site locally to check if it looks the way you want it::

    make html

If you approve, you can publish it like so::

    make github

The new version is now reachable at `github <http://tomster.github.com/sourdoughdiary/index.html>`_.