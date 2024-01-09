# The Original Crowther version (1977)

This is the source code for the original Crowther and Woods Colossal Cave
Adventure, 350-point version, in PDP-10 FORTRAN.  There have been many ports
of this, in both FORTRAN and C, but all of them can be traced back to this
version.

A notable feature of this version which made it into a few of the ports is the
concept of "cave hours".  Since the PDP-10 was a timesharing system, it was
often considered desirable to prevent people from playing games during
business hours.  The game has a "wizard mode" which allows the system
administrator to set the hours and optionally allow short demo games during
the off hours.

There is probably no point in trying to compile this code on anything other
than a PDP-10, because it depends on string packing of five characters per
word of memory.
