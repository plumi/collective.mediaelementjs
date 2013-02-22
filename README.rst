A simple integration of the `MediaElementJS <http://mediaelementjs.com/>`_ video player for Plone.

Large portions of this package have been blatantly copied from the `collective.flowplayer <http://pypi.python.org/pypi/collective.flowplayer>`_ product by Martin Aspeli.

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

Installation
============

Either use easy_install/pip or add it to your buildout. In either case, the name of the egg is ``collective.mediaelementjs``.

Then, simply install it from the ``prefs_install_products_form`` in Plone, as you would with any other Plone product.

