# ching
Ask the Oracle; get a hexagram with commentary.

This is a rewrite in JavaScript and Bootstrap of something I originally wrote using Perl.
From the `README` uploaded on February 6, 2005:

> Because I never have three coins to throw...
> 
> http://hexadecimal.uoregon.edu/ching/src.html provides ching(6), and
> also provides the text used for interpretations, data/ching.txt, scoured
> for use in data/ching.records.
> 
> http://www.catb.org/~esr/writings/taoup/html/ch06s01.html taught me
> sng(1) existed. I used it to generate hexagrams.
> 
> bin/hexagrams.pl generates the 64 hexagrams in PNG format. For non-unique
> English spellings, the second (according to the order in data/ching.txt)
> takes a trailing _ on the basename.
> 
> bin/rec2html.pl transforms data/ching.records to a series of XHTML
> documents in a single file.
> 
> bin/splithtml.pl splits the output of bin/rec2html.pl into a series
> of XHTML files. For non-unique English spellings, the filenames follow
> the hexagram names.
> 
> oracle.cgi responds when you ask the Oracle.

One day, CGI stopped working.
This version is client-side only, with Ajax to get the oracle's answer.
