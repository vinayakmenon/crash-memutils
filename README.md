crash-memutils
==============

crash-memutils is an extension module for crash utility.

To build the module from the top-level crash-<version> directory, enter:

$ cp <path-to>/memutils.c extensions
$ make extensions

$ extend extensions/memutils.so
$ memutils <options>

Supported options:
==================
p:	displays the number of pages per migrate type for all orders, for all nodes.
