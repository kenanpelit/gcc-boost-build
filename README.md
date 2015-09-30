gcc-boost-build
====================

  Bash script to install recent versions of gcc and boost on CentOS 5.x, CentOS 6.x and Mac OS X. Languages: c++, c and go. Includes tcmalloc on linux.
  
  To use it:

    $ git clone https://github.com/nelsonje/gcc-boost-build.git
    $ cd gcc-boost-build
    $ make PREFIX=<path>

  This was forked from one of Joe Linoff's gcc/boost build scripts; for more detailed information see http://joelinoff.com/blog/?p=1514.

Changelog:
----------

- supports gcc 4.9.2, boost-1.57; Forked from https://github.com/jlinoff/gcc-4.9.2-boost-1.57
