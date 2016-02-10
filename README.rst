Riglog
======

Collect runtime statistics for a Varnish Cache setup, including:

* System load statistics (cpu/disk/swap usage)
* Varnish Cache process statistics as seen by the operating system.
* varnishstat counters from within Varnish Cache.

Output files are stored to disk, and tools to convert these to CSV for further
data analysis is included.

Usage
-----

::
    ./riglog INTERVAL COUNT

To sample every `INTERVAL` [seconds] for `COUNT` times.

Good values to start with are `INTERVAL` of 1 and `COUNT` of 10 to make sure
everything is working.

Data collections from production should be at least 15 minutes long.

Output files are written to a subdirectory. (hostname__TIMESTAMP/ )

Installation
------------

On Debian/Ubuntu systems::

    apt-get install sysstat


Contact
-------

If you have any questions regarding this script, contact <lkarsten@__no_spam_please__varnish-software.com>.
