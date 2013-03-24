ABOUT
=====

libKiCad is a compilation of symbols, footprints and 3d models of various
electronics components for the KiCad EDA (http://www.kicad-pcb.org/).

The libraries are based on the Walter Lain's kicad library
(http://smisioto.no-ip.org/elettronica/kicad/kicad-en.htm).

In addition to the original libraries, the following improvements have been 
made:
+ The structure of the library have been changed to make it cross-platform
  (tested on Ubuntu and Windows).

LICENSE
=======

This library is licensed under the:
Creative Commons license v3.0, Attribution-Share Alike (CC BY-SA 3.0).
For further details see 3d/license.txt, footprint/license.txt and 
symbol/license.txt.

INSTALLATION AND USE
====================

Clone this repository into the same folder as your KiCad project folders.

Your directory should look like the following example.

<path/to/projects>
    awesomeProject
        awesomeProject.pro
        awesomeProject.sch
        awesomeProject.brd
        ...
    coolProject
        coolProject.pro
        coolProject.sch
        coolProject.brd
        ...        
    libkicad
        3d
            ...
        footprint
            ...
		symbol
			...
        README
	...

Open your project .brd file (e.g. awesomeProject.brd) in KiCad's pcbnew, go to
preferences > library, remove the default libraries and add all the .mod files
under libKiCad/footprint.

SCHEMATIC SYMBOLS
=================

Open your project .sch file (e.g. awesomeProject.sch) in KiCad's eechema, go
to preferences > library, remove the default libraries and add all the .lib
files under libKiCad/symbol.

If you need more symbols you should look at the latest KiCad official
library (https://code.launchpad.net/~kicad-lib-committers/kicad/library).

