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
* Jump to error line by double clicking on the error message (or by pressing F4). Thanks to [malickf](https://github.com/malickf)!

**NOTE 1:** The package is provided "as is" without support (see license).

**NOTE 2:** The package is based on the [TextMate package for C/C++](https://github.com/textmate/c.tmbundle). If you discover any mistakes, or find that features are missing, then you are more than welcome to contribute to the package!

**NOTE 3:** Thanks to [Paul Chaignon](https://github.com/pchaigno) and the [Linguist Project](https://github.com/github/linguist), the grammar provided in this package is now used to highlight Ox code on GitHub!


Example
------------

![Example](http://i.imgur.com/bXCRdgg.png?raw=true)


Requirements and Setup
------------

To use the package, simply clone or download the repository to your Sublime Text 2 "Packages" directory. Sublime Text 2 should then recognize .ox files. To execute Ox code from Sublime Text 2 (via Ctrl+b), you need either Ox Professional (requires license, may be obtained from [Timberlake Consultants](http://www.timberlake.co.uk/)) or Ox Console ([free to use](http://www.doornik.com/download/oxmetrics7/Ox_Console/), subject to [conditions](http://www.doornik.com/ox/licence_Ox_Console.txt)).
