Text/Markup version 0.11
========================

This library's module, Text::Markup, provides an single interface for parsing
a large number of text markup formats and converting them to HTML. It
currently supports the following markups:

* [HTML](http://whatwg.org/html)
* [Markdown](http://daringfireball.net/projects/markdown/)
* [MediaWiki](http://en.wikipedia.org/wiki/Help:Contents/Editing_Wikipedia)
* [Pod](http://search.cpan.org/perldoc?perlpod)
* [Textile](http://textism.com/tools/textile/)
* [Trac](http://trac.edgewall.org/wiki/WikiFormatting)

INSTALLATION

To install this module, type the following:

    perl Build.PL
    ./Build
    ./Build test
    ./Build install

Or, if you don't have Module::Build installed, type the following:

    perl Makefile.PL
    make
    make test
    make install

Dependencies
------------

Text-Markup requires the following modules:

* Text::Markdown 1.000004

Copyright and Licence
---------------------

Copyright (c) 2011 David E. Wheeler. Some Rights Reserved.

This module is free software; you can redistribute it and/or modify it under
the same terms as Perl itself.