======================================================================
            SERA - Tree and Forest Growth Simulation Software
======================================================================

Version 0.9: 2009.05.01
-----------

SERA is a software suite that attempts to model the growth of individual trees using empiriclly derived--or randomly chosen--values for use with allometric relationships. By modeling the behavior of an individual tree, it is possible to model population dynamics in a spatially explicit simulationspace. 

This is a development release.

email: seanth@gmail.com

DEPENDENCIES/REQUIREMENTS
_________________________
	*Python v2.5 (http://python.org/download/)
	*pyYAML v3.06 (http://pyyaml.org/wiki/PyYAML)
	*Psyco v1.6 (optional. Psyco improves the speed at which some calculations are made. This can only be used on 32-bit, 386-compatible processors, i.e. it will not work on PowerPC Macs. http://psyco.sourceforge.net/download.html)
	*ContextFree v2.2 (optional. Needed to generate graphics. http://www.contextfreeart.org/download/ContextFreeSource2.2.tgz)
	*AppleScript v1.83 (optional. Needed to automatically generate videos from graphics. This can only be used with Apple's OS X operating system.)
	*Quicktime v7.6 (optional. Needed to automatically generate videos from graphics. Because SERA uses AppleScript is to automate Quicktime, this will only work computer's running Apple's OS X. http://www.apple.com/quicktime/download/)

HOW TO USE
----------
After installing all the dependencies necessary, simply cd to the SERA folder and, in the simplest form, type:
	>python SERA.py
For more information, including command line options and ways to make species, event files and define planting locations, please see SERA HOWTO.txt

EXAMPLES
--------
For more examples, including command line options and ways to make species, event files and define planting locations, please see SERA HOWTO.txt

