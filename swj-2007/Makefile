
default: all

all: swj-all clean

clean:
	rm -rf *~ *.out *.aux *.bbl *.blg *.dvi *.idx *.ilg *.ind *.log *.toc

swj: swj-all

swj-all: swj-pdf

pdf: swj-pdf

swj-pdf:
	pdflatex Faletic
	bibtex Faletic
	pdflatex Faletic
	pdflatex Faletic
	pdflatex Faletic
