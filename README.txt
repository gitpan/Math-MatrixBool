                   =========================================
                     Module "Math::MatrixBool" Version 5.7
                   =========================================
                       for Perl version 5.000 and higher

         Copyright (c) 1995, 1996, 1997, 1998, 1999 by Steffen Beyer.
                             All rights reserved.

     This package is free software; you can redistribute it and/or modify
     it under the same terms as Perl itself.


Prerequisites:
--------------

Perl version 5.000 or higher, module "Bit::Vector" version 5.7 or higher.


Installation:
-------------

Simply install this module using the following commands:

                            % perl Makefile.PL
                            % make
                            % make test
                            % make install

(Under Windows NT, use "nmake" or "dmake" instead of "make".)


Documentation:
--------------

To see the module's documentation, use the command "man Math::MatrixBool"
(Unix) or "perldoc Math::MatrixBool" (both Unix and Win32) thereafter.


Version history:
----------------

In version 5.7, the method "Product()" has been added. This is the same
as the method "Multiplication()", except that it uses the binary or ("|")
operation instead of the binary "xor" ("^") operation as the boolean
addition operator ("+").

See the file "CHANGES.txt" in the "Bit::Vector" distribution for a log
of previous versions.


Author's note:
--------------

I hope you will find this module beneficial!

Share and enjoy!

Yours,
--
    Steffen Beyer <sb@sdm.de> http://www.engelschall.com/u/sb/
     "There is enough for the need of everyone in this world,
      but not for the greed of everyone." - Mahatma Gandhi
