phpMyAdmin - localized documentation
====================================

This repository contains localized documentation for phpMyAdmin. It
is based on master document placed in phpmyadmin repository.

To translate edit your language file in po directory, changes will be
propagated to generated documents. You can also translate online at
<https://hosted.weblate.org/projects/phpmyadmin/documentation/> and your changes
will be merged to Git.

.. image:: http://hosted.weblate.org/widgets/phpmyadmin-status-badge.png
    :alt: Translation status
    :target: https://hosted.weblate.org/engage/phpmyadmin/?utm_source=widget

Requirements
------------

For manipulating with translations, you need gettext and sphinx installed.

Usage
-----

To start new translation just add it to Makefile.

To regenerate mofiles use script make.

To obtain statistics about current translations run locales-stats.
