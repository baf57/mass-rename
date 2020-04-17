A simple bash script that allows for the mass rename of every file in a 
directory which contains the given substring. Works via globing to match files,
and can be used to add a prefix, suffix, rename the file, or do any of those
in combination.

More of a coding exercise than an attempt at making something new, although if
you don't like the perlexpr aspect of rename
(https://manpages.debian.org/stretch/rename/rename.1.en.html) or just want
something that does not require the full syntax of rename, then you could use
this instead.
