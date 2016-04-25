# haskell-papers-ereader

#### Note 1: Some of the single-column papers are in landscape mode. These are prefixed with `[LS]`.

#### Note 2: If the paper isn't here, look in [ocharles' git-annex repository](https://github.com/ocharles/papers/blob/master/README.md). robbinch's [`Papers` git repository](https://github.com/robbinch/Papers) may also contain what you're looking for.

I use [k2pdfopt](http://www.willus.com/k2pdfopt/) to turn the typical 2-column papers in PDF format into a PDF suitable for an e-reader.  It seems to handle figures well, too, so I'm happy with it.

I've also taken some of the single-column papers with *huge* margins and ran them through the tool to make the font bigger on an e-reader.

I use the GUI on Windows (in administrator mode) to generate the PDFs, but here are the command-line options:

```
-dev kbhd -mode 2col -c -om 0.2
```

This takes a 2-column paper and generate a PDF suitable for a Kobo Aura HD and sets a 0.2 inch margin around the document.
Here's an example:

![Example on the Kobo Aura HD](http://i.imgur.com/jPjzrQoh.jpg?1)
