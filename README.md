**LEMPress is currently being developed and is not ready for use. If you've stuMbled across this repository somehow and your interested in using LEMPress, add it to you watch list and check back regularly for the first stable release.**

About LEMPress
=========
  LEMPress is a super easy to use build script, for setting up a Wordpress optimized server. 

Strategy
=====
  LEMPress strives to get the highest performance possible while keeping stability and security in mind. That's why instead of using the latest PHP build from a PPA or source, it uses good ol' dependable core Ubuntu repos. That also means LEMPress uses fast cgi instead of the faster fpm, again for stability and security. The same goes for Nginx and MySQL versions.

About the Stack
==========
  It's essentially a LEMP stack (Linux/Nginx/MySQL/PHP).
  Varnish and Memcache are also on board.

Supported OS
=========
  Ubuntu 12.04 LTS x64

Scripting Language
============
  Bash

How to Use:
========
        sudo apt-get install openssh-server git-core
        git clone git://github.com/okor/LEMPress.git
        cd LEMPress
        bash build

