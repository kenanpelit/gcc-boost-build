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

* Many things:
  * Added more dependences to improve builds on barebones/out-of-date
   systems: m4-1.4.17, flex-2.5.39, bison-3.0.4, libbzip2-1.0.6, zlib-1.2.8.
  * Disabled Python component of Boost.
  * Reduced some (probably?) wasted work and fixed an installation
    problem in Boost build.
  * Added module file for use with "Environment Modules" package
    commonly found on HPC clusters.
  * Improved behavior of script when re-run on partially-completed build.
* updated to gcc 4.9.3, boost 1.59, mpfr 3.1.3, gperftools 2.4, binutils 2.25, mpc 1.0.3;
  added gdb, version 4.7.10
* supports gcc 4.9.2, boost-1.57; Forked from https://github.com/jlinoff/gcc-4.9.2-boost-1.57
