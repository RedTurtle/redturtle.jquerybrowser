.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide_addons.html
   This text does not appear on pypi or github. It is a comment.

==============================================================================
redturtle.jquerybrowser
==============================================================================

This Plone add-on adds a small js script that contains the jQuery code for the ``.browser`` function.
This function was removed from jQuery starting from version 1.9, but it's still required for some projects for browser identification.

The original script added by this package is found here https://github.com/gabceb/jquery-browser-plugin/blob/master/dist/jquery.browser.min.js.


Documentation
-------------

Full documentation for end users can be found in the "docs" folder.


Compatibility
-------------

redturtle.jquerybrowser works with every plone.app.jquery_ version > 1.9.
You don't need this package if you are using an older version of plone.app.jquery_.

.. _plone.app.jquery: https://github.com/plone/plone.app.jquery

Installation
------------

Install redturtle.jquerybrowser by adding it to your buildout::

    [buildout]

    ...

    eggs =
        redturtle.jquerybrowser


and then running ``bin/buildout``


Contribute
----------

- Issue Tracker: https://github.com/RedTurtle/redturtle.jquerybrowser/issues
- Source Code: https://github.com/RedTurtle/redturtle.jquerybrowser


Support
-------

If you are having issues, please let us know.
We have a mailing list located at: sviluppoplone@redturtle.it


License
-------

The project is licensed under the GPLv2.
