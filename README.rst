Introduction
============

``file-metadata-wikibot`` is a python package that aims to analyze files and find
metadata that can be used from it on Wikipedia Commons by using pywikibot.

For more information on the package visit `pywikibot-catfiles/file-metadata
<https://github.com/pywikibot-catfiles/file-metadata>`__.

Development
===========

Docker
------

To pull the ``latest`` docker image use::

    $ docker pull drtrigon/file-metadata-wikibot

Supported tags and respective ``Dockerfile`` links:
 * ``latest``, ``ubuntu-14.04`` (`docker/Dockerfile <https://github.com/drtrigon/docker-file-metadata-wikibot/blob/master/Dockerfile>`__)
 * `show all... <https://hub.docker.com/r/drtrigon/file-metadata-wikibot/tags/>`__

For more information about this image and its history, please see
``pywikibotcatfiles/file-metadata`` (`on github <https://github.com/pywikibot-catfiles/file-metadata>`__).
This image is updated via ...

Usage
-----

To use the code, run the docker image as container::

    $ docker run -it --rm drtrigon/file-metadata-wikibot bash

and then setup pywikibot configuration::

    # wikibot-create-config

after that you can run a bot as::

    # wikibot-filemeta-log -help

or::

    # wikibot-filemeta-simple -help


Build status
------------

.. image:: https://travis-ci.org/drtrigon/docker-file-metadata-wikibot.svg?branch=master
   :target: https://travis-ci.org/drtrigon/docker-file-metadata-wikibot

.. image:: https://travis-ci.org/drtrigon/install-file-metadata-wikibot.svg?branch=master
   :target: https://travis-ci.org/drtrigon/install-file-metadata-wikibot

Credits
-------

This package has been derived from
`pywikibot-compat <https://gerrit.wikimedia.org/r/#/admin/projects/pywikibot/compat>`__.
Specifically, the script ``catimages.py`` which can be found at
`pywikibot-compat/catimages.py <https://phabricator.wikimedia.org/diffusion/PWBO/browse/master/catimages.py>`__.
These packages were created by `DrTrigon <mailto:dr.trigon@surfeu.ch>`__ who
is the original author of this package.

LICENSE
=======

.. image:: https://img.shields.io/github/license/AbdealiJK/file-metadata.svg
   :target: https://opensource.org/licenses/MIT

This code falls under the
`MIT License <https://tldrlegal.com/license/mit-license>`__.
Please note that some files or content may be copied from other places
and have their own licenses. Dependencies that are being used to generate
the databases also have their own licenses.
