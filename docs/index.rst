=======================================
Welcome to mozilla.org's documentation!
=======================================

**bedrock** is the code name of the new mozilla.org. It is bound to be as
shiny, awesome, and open sourcy as always. Perhaps even a little more.

bedrock is a web application based on `Django
<http://www.djangoproject.com/>`_/`Playdoh
<https://github.com/mozilla/playdoh>`_.

Patches are welcome! Feel free to fork and contribute to this project on
`Github <https://github.com/mozilla/bedrock>`_.


Contents
--------

.. toctree::
   :maxdepth: 1

   l10n
   php
   

Localization
------------

Looking for help on how l10n works on bedrock? :ref:`Look here <l10n>`
for more details.

Installation
------------

It's a simple `Playdoh
<http://playdoh.readthedocs.org/en/latest/index.html>`_ instance, and
works like django.::

    git clone --recursive git://github.com/mozilla/bedrock.git
    cd bedrock
    cp settings/local.py-dist settings/local.py
    ./manage.py runserver

This section will be expounded soon.

PHP
---

Looking to setup the PHP version of the site? `Look here
<php-install>` for more details.

Interested in more details of the PHP version of the site? :ref:`Read
this <php>` for more information on the history of the site, how the
code works, and more.


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
