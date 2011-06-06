===============
sjconf-lilo
===============

sjconf-lilo is a simple plugin to manage lilo configuration file from sjconf.

License
======

sjconf-lilo is released under the `GNU LGPL 2.1 <http://www.gnu.org/licenses/lgpl-2.1.html>`_.


Build and installation
=======================

Bootstrapping
-------------

sjconf-lilo uses the autotools for its build system.

If you checked out code from the git repository, you will need
autoconf and automake to generate the configure script and Makefiles.

To generate them, simply run::

    $ autoreconf -fvi

Building
--------

sjconf-lilo builds like your typical autotools-based project::

    $ ./configure && make && make install


Development
===========

We use `semantic versioning <http://semver.org/>`_ for
versioning. When working on a development release, we append ``~dev``
to the current version to distinguish released versions from
development ones. This has the advantage of working well with Debian's
version scheme, where ``~`` is considered smaller than everything (so
version 1.10.0 is more up to date than 1.10.0~dev).


Authors
======

sjconf-lilo was created at SmartJog by :

* Clément Bœsch <clement.boesch@smartjog.com>
* Gilles Dartiguelongue <gilles.dartiguelongue@smartjog.com>
* Jean-Philippe Garcia Ballester <jeanphilippe.garciaballester@smartjog.com>
* Nicolas Noirbent <nicolas.noirbent@smartjog.com>
* Philippe Bridant <philippe.bridant@smartjog.com>
* Rémi Cardona <remi.cardona@smartjog.com>
* Thomas Meson <thomas.meson@smartjog.com>

