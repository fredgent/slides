

#LATEX=latex
LATEX=pdflatex
BIBTEX=bibtex

#default=redraft.dvi
default=Nordita23.pdf

#redraft.dvi:redraft.tex my.bib Makefile
Nordita23.pdf:Nordita23.tex refs.bib Makefile 
	$(LATEX) Nordita23 
	$(BIBTEX) Nordita23
	$(LATEX) Nordita23
	$(LATEX) Nordita23

clean:
	rm -f *.aux  *.nav *.out *.snm *.toc *.blg *.end *.log *~
pristine: clean
	rm -f *.bbl 

