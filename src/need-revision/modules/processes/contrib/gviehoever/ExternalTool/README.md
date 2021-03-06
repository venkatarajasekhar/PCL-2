ExternalTool
------------


ExternalTool is a PCL module that permits to execute external processes from within PixInsight  - in the same way as internal processes.
The external program simply needs to support the FITS format and allow for control via a command line.

As examples, it comes with 4 external programs that permit to

* compute intensity contours in an image,
* create a visibility diagram for the planets, sun and moon,
* platesolve an image using the Astrometry.net blind solver web service, and 
* launch the interactive sky atlas Aladin that can connect to a large number of astronomical databases.

**This release is a Beta version. It likely still has bugs. Also, it has been developed and tested only on Fedora21 (Linux). There is no known reason why
the module should not work on other PI platforms - but as usual there are probably minor differences that can make life interesting.
Contributions of code, bug reports, fixes are welcome!**

## Directories
Here a short list of what you find where:

* **./**: contains the sources
* **linux/g++/**: contains the Makefile for Linux. Makefiles for other platforms are not (yet) provided, but can be created using the
  PixInsight Makefile generator. Compiling on other platforms has not yet been tested.
* **ExampleTools/**: sources of the example executables.
* **piDoc/**: sources of the module documentation.
* **compiled/linux/g++/x86/Release/**: For your convenience: a copy of the binary module for Linux. Will be removed once released with the regular PI distribution.
* **compiled/html/ExternalTool/**: For your convienience: html version of the documentation in piDoc. Will be removed once released with the regular PI distribution.

##Change Log

* 2015-02-15 Initial release

Enjoy!

Georg
