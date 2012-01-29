.. _installing:

**********
Installing
**********

*pyregion* is registered in pypi, thus you can install it by ::

 pip install pyregion

This will also install pyparsing if not installed.

Also, pyregion source can be downloaded from the following page.

* `Download <http://github.com/leejjoon/pyregion/downloads>`__

However, pyregion is a personal hobby project and still in development
(likely to be buggy).  And it is recommended that you fetch the source
code by cloning my git repository for any recent bug fix. ::

 # git clone git://github.com/leejjoon/pyregion.git
 # cd pyregion
 # python setup.py install


Dependencies
============

**Requirements**

Being based on pyparsing module, pyparsing need to be installed to use
pyregion. Optionally, you also requires pywcs
module installed for coordinate
conversion. Displaying regions is supported for matplotlib.  Some
example uses pywcsgrid2.

By default, pyregion build a filtering module, which requires a C compiler.
If you don't want, edit "setup.py" ::

  WITH_FILTER = False


pyparsing
---------
* REQUIRED
* `Homepage <http://pyparsing.wikispaces.com/>`__

pywcs
-----
* OPTIONAL
* used for coordinate conversions
* `Homepage <https://trac.assembla.com/astrolib/>`__
* or `Astropy <https://github.com/astropy/astropy/>`__

pyfits
------
* OPTIONAL
* `Homepage <http://www.stsci.edu/resources/software_hardware/pyfits>`__


matplotlib
----------
* OPTIONAL
* `Homepage <http://matplotlib.sourceforge.net/>`__

pywcsgrid2
----------
* OPTIONAL
* `Homepage <http://leejjoon.github.com/pywcsgrid2/>`__
