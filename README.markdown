netlist
=======

netlist is a Perl script that extracts address and network information
from the computer (i.e. 'localhost') and returns it as a simple string
suitable for inclusion in other scripts -- a firewall script for example.

For details, run:

    ./netlist --help


Requirements
------------

netlist runs on Linux.

It requires Perl 5 version 5.10.1 or later, and the following non-core modules:

* NetAddr::IP


Installation
------------

There is not (yet) an installation script or package.  All you need to do is

1.  Download the script and all the related files by clicking on the
    'Downloads' button on https://github.com/StarsoftAnalysis/netlist
    and unpack the files into a suitable directory on your computer.

2.  Run the script, with a command something like this:

        ./netlist --domain ipv6 addresses


**************************************************************
This is part of the netlist documentation.<br>
Copyright &copy; 2012  Chris Dennis  chris@starsoftanalysis.co.uk<br>
See the file fdl-1.3.txt for copying conditions.
**************************************************************
 
