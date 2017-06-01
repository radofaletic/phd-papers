
DOCUMENT = abel

default: all

all: pdf clean-tex

pdf:
	pdflatex $(DOCUMENT)
	pdflatex $(DOCUMENT)

power-law: power-law-cuts

power-law-cuts:
	latex power-law-cuts
	latex power-law-cuts
	dvips power-law-cuts -o power-law-cuts.ps

clean: clean-tex
	rm -rf $(DOCUMENT).pdf power-law-cuts.ps

clean-tex:
	rm -rf *~ *.out *.aux *.bbl *.blg *.dvi *.idx *.ilg *.ind *.log *.toc
