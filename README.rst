An integration of the `MediaElementJS <http://mediaelementjs.com/>`_ 
audio&video player for Plone.

Large portions of this package have been blatantly copied from the
`collective.flowplayer <http://pypi.python.org/pypi/collective.flowplayer>`_
product by Martin Aspeli.

What it does
============

Once installed, you can upload MP4 (H.264), Ogg, WebM, FLV, WMV, MPEG
and QuickTime (``.mov`` and ``.qt``) files and they will automatically use a
default view that renders the video using the MediaElementJS player.

MediaElementJS uses a HTML5 ``<video>`` tag, so any browser that can
render the media natively will do so, and uses plugins if either the
codec or the ``video`` tag is not supported. See the `MediaElementJS
browser and device support chart <http://mediaelementjs.com/>`_ for
details.

You can also upload MP3, Ogg, Oga, M4A, WebMa file, they will automaticly
use the mediaelement view using a HTML5 ``<audio>`` tag.

Installation
============

.. image:: https://secure.travis-ci.org/collective/collective.mediaelementjs.png
    :target: http://travis-ci.org/collective/collective.mediaelementjs

This addon can be installed has any other addons. please follow official
documentation_

.. _documentation: http://plone.org/documentation/kb/installing-add-ons-quick-how-to

Dependencies:

* hachoir_core
* hachoir_metadata
* hachoir_parser

Credits
=======

People
------

* Tom Lazar <tom@tomster.org> (author)
* Servilio Afre Puentes <afrepues@mcmaster.ca> (maintainer)
* Markos Gogoulos <mgogoulos@unweb.me>
* JeanMichel FRANCOIS <toutpt@gmail.com>

Companies
---------

* Unweb.me https://unweb.me/
* Makina-Corpus http://www.makina-corpus.com
