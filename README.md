purdue-rhipe-group
==================

This is a repository for code and documentation work for the Purdue class STAT 695, "The R Programming Language."

We're currently pulling over the existing work from CVS on the internal machine where hardly anyone can see it. :)

Project status
===============

We have 4 subprojects:

* Documentation (general)
* Timings - how fast does RHIPE run on the small cluster at Purdue?
* rmr comparison - install and try out rmr, the RHadoop system from Revolution Computing, to see how it compares to RHIPE.
* Using RHIPE on EC2 (status: waiting for space from Amazon)

How to edit the documentation
==============================

The documentation is written in LaTeX, a typesetting language. If you're not familiar with LaTeX, simply edit the files with the suffix ".tex" as if they were plaintext, being careful not to touch anything in {brackets} or after \backslashes because they are Magic Formatting Syntax. You may be able to pick up some syntax just by looking at the document structure, or do a search for "LaTeX tutorial" online and you'll find resources like http://www.tug.org/twg/mactex/tutorials/ltxprimer-1.0.pdf.

After you have edited filename.tex, run the following two commands (in Linux) to generate a pdf from it.

latex filename.tex
dvipdf filename.dvi 

The first command generates a .dvi from the .tex, the second generates a .pdf from the .dvi.