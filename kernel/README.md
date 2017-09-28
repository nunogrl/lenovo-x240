kernel
======

This kernel is based on the work of Markus Demleitner and his instructions can be found at http://www.tfiu.de/x240/

Considerations
--------------

The only reason I've been making modifications on the kernel is because there 
are some components that I realize I miss for my work or for specific 
periferics.

Building
--------

To build the kernel just type

    make-kpkg --append-to-version -thinkpadx240 --revision 2 binary kernel_headers
