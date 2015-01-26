Ox Plugin for Sublime Text 2
=====================================

by Andreas Hetland
[www.andreashetland.com]

*Latest revision:* 2015-01-26. 

**NOTE:** The package has so far *only* been tested with the setup consisting of Sublime Text 2 and Ox Professional 7 on a 64-bit Windows 7 machine. The package is provided "as is", and without support. Contributions are encouraged :-)

The package currently provides the following features for working with Ox code in Sublime Text 2:
* Syntax highlighting (based on OxEdit and OxMetrics).
* Snippets for if, else, for, and main.
* A build system (defaulting to executing on two CPU cores via the -rp2 flag).
* Line and block comments.
* Indentation rules.

Requirements and Setup
------------

The package requires either Ox Professional (requires license, may be obtained from [Timberlake Consultants](http://www.timberlake.co.uk/)) or Ox Console ([free to use](http://www.doornik.com/download/oxmetrics7/Ox_Console/), subject to [conditions](http://www.doornik.com/ox/licence_Ox_Console.txt)). To use the package, do the following:

1. Clone or download the repository to your Sublime Text 2 "Packages" directory.
2. Rename the new directory from "sublime-text-ox" to "Ox".
3. Add Ox Console to your $PATH. On Windows 7, the string to be added will look something like "C:\Program Files\OxMetrics7\Ox\bin64". See [how to add environment variables on Windows 7](http://www.itechtalk.com/thread3595.html) if you do not know what to do.

Sublime Text 2 should now recognize .ox files.


Caveat
------------

The package is based on the language package for C/C++. I do not know regular expressions (yet), so I have just copied the C/C++ patterns that fit the Ox language. If you discover any mistakes, or find that features are missing, then you are more than welcome to contribute to the package!
