Ox Plugin for Sublime Text 2
=====================================

by Andreas Hetland
[www.andreashetland.com]

*Latest revision:* 2015-02-02. 

**NOTE:** The package is provided "as is" without support (see license below). Contributions are encouraged :-)

The package currently provides the following features for working with Ox code in Sublime Text 2:
* Syntax highlighting (based on OxEdit and OxMetrics).
* Snippets for if, else, for, and main.
* A build system (defaulting to executing on two CPU cores via the -rp2 flag).
* Line and block comments.
* Indentation rules.


Requirements and Setup
------------

The package requires either Ox Professional (requires license, may be obtained from [Timberlake Consultants](http://www.timberlake.co.uk/)) or Ox Console ([free to use](http://www.doornik.com/download/oxmetrics7/Ox_Console/), subject to [conditions](http://www.doornik.com/ox/licence_Ox_Console.txt)). To use the package, simply clone or download the repository to your Sublime Text 2 "Packages" directory. Sublime Text 2 should then recognize .ox files.


Caveat
------------

The package is based on the [TextMate package for C/C++](https://github.com/textmate/c.tmbundle). I do not know regular expressions (yet), so I have selectively reused/modified the C/C++ patterns to fit the Ox language. If you discover any mistakes, or find that features are missing, then you are more than welcome to contribute to the package!


License
------------

The MIT License (MIT)

Copyright (c) 2015 Andreas Hetland

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
