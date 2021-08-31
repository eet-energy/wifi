wifi-ap-force
-------------

Wifi provides a command line wrapper for iwlist and /etc/network/interfaces
that makes it easier to connect the WiFi networks from the command line.  The
wifi command is also implemented as a library that can be used from Python.

This fork takes care of the "ap-force" option when running iw.
Also, the binary is not /sbin/iwlist anymore, but iw directly (/usr/sbin/iw),
therefore the command is a bit different.

It's a drop-in replacement of the original package.

::

    # pip install wifi-ap-force
    # wifi --help

The original documentation for wifi lives at https://wifi.readthedocs.org/en/latest/.
