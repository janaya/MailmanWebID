.. _ref-introduction:

========================
About MailmanWebID
========================

WebID authentication and authorization for Mailman

By adding WebID support to Mailman, this project aims at:
(1) providing a simple subscription and authentication
mechanism without the need for the user of creating
another user/password. 
(2) producing  a mechanism to evaluate a set of trust
rules that can be used to decide
whether an user can join or create a list, for
automated moderation, and granular access control to
archives and profiles. 

Project URL
~~~~~~~~~~~~
`MailmanWebID`_

Technologies
============

* `WebID`_ , a decentralized technology that leverages X.509 Certificates and provides and open standard for identity and login.
* `Mailman`_ 3.x, provides REST interface and general plugins architecture for `GNU Mailman`_.
* `django-mailman`_, a Django webapp that provide a more usable Mailman interface making use of the Mailman REST API.
* `django-foafssl`_, a webapp to generate WebId certificates and to provide WebId authentication module for Django.


Install
=======
No code yet, see the file InitialIdeas

Download
========
You can download this project in either
 * `zip`_ or
 * `tar`_ formats.
 
You can also clone the project with `Git`_ by running::
    $ git clone git://github.com/janaya/MailmanWebID

Bugs and features
=================
If you wish to signal a bug or report a feature request, please fill-in an issue on the `MailmanWebID issue tracker`_

License
=======
`LGPL v3`_

Contact
========
(julia.anaya at gmail dot com)

.. _MailmanWebID: http://janaya.github.com/MailmanWebID/
.. _WebID: http://WebID.info/
.. _Mailman: http://wiki.list.org/display/DEV/Mailman+3.0
.. _django-mailman: http://wiki.list.org/display/DEV/Web+Interface+Status
.. _django-foafssl: https://github.com/duy/django-foafssl
.. _GNU Mailman: http://www.gnu.org/software/mailman/index.html
.. _zip: http://github.com/janaya/MailmanWebID/zipball/master
.. _tar: http://github.com/janaya/MailmanWebID/tarball/master
.. _MailmanWebID issue tracker: https://github.com/janaya/MailmanWebID/issues
.. _Git: http://git-scm.com
.. _LGPL v3: http://www.gnu.org/licenses/lgpl.html
