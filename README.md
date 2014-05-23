bsdlibc
=======

porting NetBSD libc to a standalone  tarball  in an attempt to make a BSD userland on linux.

Project
-------
In a bootstrapped partition, LLVM/Clang compiled LLVM/Clang, and LLVM/Clang & pkgsrc (NetBSD ports package manager) have been installed.
The next step in creating a NetBSD userland on linux will be to install libc from NetBSD's libc source.

Building
-------

go to src/lib/libc, and execute make.sh
requires llvm and bmake

Roadmap
-------

Make a ```configure``` file for building the source for this NetBSD CVS module
