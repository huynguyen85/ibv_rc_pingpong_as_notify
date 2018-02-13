ibv_rc_pingpong_as_notify
===========

as_notify interrupt is a PowerPC P9 feature that allows PCI device
to directly wake up a userspace sleeping thread.

This tool is reusing the existing ibv_rc_pingpong. The only difference
is with option "-e", the as_notify interrupt is used instead of the
MSI interrupt.

Supported OS
------------

* GNU/Linux

Packages
--------

None at this time.

Authors
-------

* Huy Nguyen <huyn@mellanox.com>

Licensed under GPLv3 (or later) <http://www.gnu.org/licenses/gpl-3.0.txt>
