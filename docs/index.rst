====================
redturtle.jquerybrowser
====================

This Plone add-on adds a small script that contains the jQuery code for the ``.browser`` property.
This function was removed from jQuery starting from version 1.9, but it's still required by some projects for browser identification.

The original script added by this package is found here https://github.com/gabceb/jquery-browser-plugin/blob/master/dist/jquery.browser.min.js.

You don't need this package if you are using an older version of plone.app.jquery_. (For example, Plone 4.3 runs version 1.7)

.. _plone.app.jquery: https://github.com/plone/plone.app.jquery


Why do we need this?
--------------------

Sometimes, when developing a website, you need to use a specific jQuery plugin. When doing this, you might encounter this error in the browser console::

    TypeError: $.browser is undefined

or::

    TypeError: jQuery.browser is undefined

If this happens, and you really need to use jQuery > 1.9 and the ``jQuery.browser`` property, then you will need to add some code that implements that.
