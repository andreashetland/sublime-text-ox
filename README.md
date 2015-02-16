Ox Plugin for Sublime Text 2
=====================================

by Andreas Hetland
[www.andreashetland.com]

*Latest revision:* 2015-02-16. 

The package provides the following features for working with Ox code in Sublime Text 2:
* Syntax highlighting (based on OxEdit and OxMetrics).
* Snippets for if, else, for, and main.
* A build system (defaulting to executing on a single CPU core via the "-rp1" flag).
* Line and block comments.
* Indentation rules.

**NOTE 1:** The package is provided "as is" without support (see license). Contributions are encouraged!


Requirements and Setup
------------

The package requires either Ox Professional (requires license, may be obtained from [Timberlake Consultants](http://www.timberlake.co.uk/)) or Ox Console ([free to use](http://www.doornik.com/download/oxmetrics7/Ox_Console/), subject to [conditions](http://www.doornik.com/ox/licence_Ox_Console.txt)). To use the package, simply clone or download the repository to your Sublime Text 2 "Packages" directory. Sublime Text 2 should then recognize .ox files.


Caveat
------------

The package is based on the [TextMate package for C/C++](https://github.com/textmate/c.tmbundle). I do not know regular expressions (yet), so I have selectively reused/modified the C/C++ patterns to fit the Ox language. If you discover any mistakes, or find that features are missing, then you are more than welcome to contribute to the package!
