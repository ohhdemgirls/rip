rarchives' album ripper
=======================

about
-----

download & provide zips for image albums on various websites.

implementation
--------------

[http://rip.rarchives.com/](http://rip.rarchives.com)

extensibility
-------------

rippers for various sites are in the [/sites/](https://github.com/4pr0n/rip/tree/master/sites) subdirectory.

all site rippers extend the [basesite.py](https://github.com/4pr0n/rip/blob/master/sites/basesite.py) super class. this file contains documentation about required overrides and other helper methods.

a simple site ripper example is [site_instagram.py](https://github.com/4pr0n/rip/blob/master/sites/site_instagram.py) which is (currently) less than 50 lines long and uses lots of the helper methods in basesite.

license
-------

licensed under the [GNU GPL v2](http://www.gnu.org/licenses/gpl-2.0.txt) public license.
