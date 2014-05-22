bsdlibc
=======

porting NetBSD libc to a standalone  tarball  in an attempt to make a BSD userland on linux.

Project
-------
In a bootstrapped partition, LLVM/Clang compiled LLVM/Clang, and LLVM/Clang & pkgsrc (NetBSD ports package manager) have been installed.
The next step in creating a NetBSD userland on linux will be to install libc from NetBSD's libc source.

Getting the source
-------
To get the libc source from the NetBSD CVS tree:
Define environment variables for cvs location

```export CVS_RSH=ssh```

```export CVSROOT=anoncvs@anoncvs.se.netbsd.org:/cvsroot```

And download the specific libc module of the CVS tree

```cvs checkout -v -A -P src/lib/libc```

This source was checkedout on May 22, 2014