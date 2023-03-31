

#LATEX=latex
LATEX=pdflatex
BIBTEX=bibtex

#default=redraft.dvi
default=Imagine23.pdf

#redraft.dvi:redraft.tex my.bib Makefile
Imagine23.pdf:Imagine23.tex refs.bib Makefile 
	$(LATEX) Imagine23 
	$(BIBTEX) Imagine23
	$(LATEX) Imagine23
	$(LATEX) Imagine23

clean:
	rm -f *.aux  *.nav *.out *.snm *.toc *.blg *.end *.log *~
pristine: clean
	rm -f *.bbl 

