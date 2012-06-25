Introduction
============

This addon register nomensa_'s mediaplayer_ into Plone.

Version: #068525783d235c16c9f62473b7983eead75827d4

About Nomensa Media Player
==========================

The Nomensa accessible media player is a flexible multimedia solution for
websites and intranets. The core player consists of JavaScript wrapper
responsible for generating an accessible HTML toolbar for interacting with a
media player of your choice. We currently provide support for YouTube (default),
Vimeo and JWPlayer although it should be possible to integrate the player with
almost any media player on the web (provided a JavaScript api for the player
in question is available).

How to update this addon (for developers)
=========================================

* Download the current master on github:
https://github.com/nomensa/Accessible-Media-Player
* Remove core/javascript/swfobject
* Put 'core' and 'custom' folders in collective/js/nomensa/resources
* Update README.rst's version

Credits
=======

Companies
---------

|cirb|_ CIRB / CIBG

* `Contact CIRB <mailto:irisline@irisnet.be>`_

Authors
-------

- JeanMichel FRANCOIS aka toutpt <toutpt@gmail.com>

.. Contributors

.. |cirb| image:: http://www.cirb.irisnet.be/logo.jpg
.. _cirb: http://cirb.irisnet.be
.. _nomensa_: http://www.nomensa.com
.. _mediaplayer: https://github.com/nomensa/Accessible-Media-Player
