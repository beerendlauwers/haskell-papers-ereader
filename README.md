# haskell-papers-ereader

I use [k2pdfopt](http://www.willus.com/k2pdfopt/) to turn the typical 2-column papers in PDF format into a PDF suitable for an e-reader.  It seems to handle figures well, too, so I'm happy with it.

I've also taken some of the single-column papers with *huge* margins and ran them through the tool to make the font bigger on an e-reader.

I use the GUI on Windows (in administrator mode) to generate the PDFs, but here are the command-line options:

```
-dev kbhd -mode 2col -c -om 0.2
```

This takes a 2-column paper and generate a PDF suitable for a Kobo Aura HD and sets a 0.2 inch margin around the document.
Here's an example:

![Example on the Kobo Aura HD](http://i.imgur.com/jPjzrQoh.jpg?1)
