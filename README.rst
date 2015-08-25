riglog
======

Collect runtime statistics for a Varnish Cache setup.


Requirements
------------

On Debian/Ubuntu systems:

    apt-get install sysstat


Usage
-----

    ./riglog INTERVAL COUNT

To sample every INTERVAL (in seconds) for COUNT times.

Good values to start with are INTERVAL=1 and COUNT=10 to make sure
everything is working.

Data collections from production should be at least 15 minutes long.

Output files are written to a subdirectory. (hostname__TIMESTAMP/ )


Contact
-------

If you have any questions regarding this shell hack, contact
me at lkarsten@__no_spam__varnish-software.com.

Varnish Software customers is recommended to use normal support channels.

