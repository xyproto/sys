sys
===

Features
--------

* Wraps systemctl and service/chkconfig.
* Will never believe that "start" or "stop" is the name of a service.
* Will accept a different order of arguments. Both "status myservice" and "myservice status" is okay.

Tip
---

* Let your user execute /usr/bin/systemctl (or /sbin/service + /sbin/ckgconfig) with sudo without a password for added comfort (and a slightly increased security risk)
