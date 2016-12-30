[![Build Status](https://travis-ci.org/ibara/yacc.svg?branch=master)](https://travis-ci.org/ibara/yacc)
yacc
====
`yacc`, or `oyacc`, is a portable version of the OpenBSD Yacc program.

It is suitable for ensuring standard Yacc compliance, for older Unix machines
that do not have a free Yacc or have a very old Yacc, or for users that do not
need the bells and whistles of `byacc` or `bison`.

`yacc` has no dependencies other than libc. It is known to build and run on all
*BSD flavors, Linux, Mac OS X, Cygwin, AIX, and Solaris. It is very likely to
run on other Unix flavors; please let me know if you are using this on a Unix
not listed here so that I may add it to the list.

Compiling
---------
To build, run:
```
$ ./configure
$ make
# make install
```

Testing
-------
Tested on Linux and Mac OS X using TravisCI. *BSD, Cygwin, AIX, and Solaris
testing done manually. AIX 5.1L and Solaris 8 are used to help ensure backwards
compatibility.

Licensing
---------
All C files in the top level directory are 3-clause BSD licensed. Some files in
the `portable/` directory are ISC licensed. Everything else is Public Domain.

Get a tarball
-------------
https://devio.us/~bcallah/yacc/yacc-20161230.tar.gz
