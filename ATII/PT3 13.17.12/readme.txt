% readme.txt for the PT3 design
% 2010/12/03, v1.20

The 31 files included in this distribution are:

amsthdoc.pdf
amsthm.sty
appendixA.tex
appendixB.tex
appendixC.tex
authors.ind
cambridgeauthordate.bst
cantor1.eps
chap1.tex
chap2.tex
chap3.tex
chap4.tex
chap5.tex
floatpag.sty
multind.sty
myriad-pt1.sty
natbib.dtx
natbib.sty
percolation.bib
PT3.cls
PT3box.eps
PT3chrule.eps
PT3guide.bbl
PT3guide.pdf
PT3guide.tex
PT3header.eps
PT3marginbox.eps
PT3secrule.eps
readme.txt
rotating.sty
subject.ind

************* TABLES *************

Please note that due to the layout of tables in the PT3 design, they will need to be keyed slightly differently. Please refer to PT3guide.pdf for instructions.

************* STYLE FILES *************

tikz.sty is normally included in the LaTeX distribution. If not, it can be downloaded from the Comprehensive TeX Archive Network http://www.ctan.org/

************* TO RUN THE FILES *************

We have commented out the lines which call in the Times and Adobe Myriad Pro Condensed fonts. You may uncomment them if you have these packages - see Section 1.5 of the guide.

To run the guide through LaTeX, you need to run something like this (depending on your installation):

  latex PT3guide

Run this three times, then make a PS or PDF using a driver such as dvips.