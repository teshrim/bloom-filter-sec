main.dvi : *.tex
	latex main

pdf: *.tex
	pdflatex main

full : *.tex
	latex main
	bibtex main
	latex main
	latex main
	pdflatex main

bib : *.tex
	latex main
	bibtex main
	latex main
	latex main


