
TLOAD for OSX

tload was one of my favorite time wasters on Linux, and I really missed it on OSX.  So I hacked up the Linux source, put everything together, and here it is.

Download and copy the executable to /usr/bin ( or anyplace you like )

To compile the source
        cc -o tload tload.c



TLOAD 

graphic representation of system load average

SYNOPSIS

tload [ -V ] [ -s scale ] [ -d delay ] [ tty ]
DESCRIPTION

tload prints a graph of the current system load average to the specified tty (or the tty of the tload process if none is specified). The -s scale option allows a vertical scale to be specified for the display (in characters between graph ticks); thus, a smaller value represents a larger scale, and vice versa.
The -d delay sets the delay between graph updates in seconds.

AUTHORS

Branko Lankester
David Engel <david@ods.com>
Michael K. Johnson (johnsonm@sunsite.unc.edu)
Greg Coleman

