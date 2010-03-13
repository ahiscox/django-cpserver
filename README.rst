NOTE: This doesn't currently work, static files are being wrapped in html,body,pre tags unfortunately. 
I am working on a fix, when I have some time here soon; I've had something submitted that might work but 
just haven't had time. If you wonder why JS and CSS isn't working, this is why. 

Requirements
============
CherryPy_

.. _CherryPy: http://www.cherrypy.org/

Installation
============

1. Put ``django_cpserver`` on your ``PYTHONPATH``.
2. Add ``django_cpserver`` to your ``INSTALLED_APPS``.

Usage
=====

Run ``./manage.py runcpserver help`` from within your project directory

Acknowledgements
================

Idea and code snippets borrowed from `Loic d'Anterroches`__, adapted to run as a management command

__ http://www.xhtml.net/scripts/Django-CherryPy-server-DjangoCerise