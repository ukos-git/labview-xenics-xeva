# xenics-xeva-labview

Added first standalone version for reading parameters and images from a XENICS Xeva Camera (320x256, 100Hz).

The program is actually part of a bigger program. It can be run as a standalone from xeva-main. The subvis follow the specifications from the main program. xeva-main is the composition of all the vis present in the program. start from here to adapt to your needs.

Installation of SDK:

* install XENICS SDK (32bit) > 2.5
* install [vi package manager](http://jki.net/vipm)
* install LabView SDK via vipm

note: labview SDK and XENICS SDK are supplied by XENICS.


Getting the VI to work:

* load the new dependencies from subfolder
* in xeva-init please specify your config and correction files or select automatic/semiautomatic as preferred method.
