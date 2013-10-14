DOCUMENT = presentation

document : $(DOCUMENT).tex
	pdflatex $(DOCUMENT).tex
	bibtex $(DOCUMENT).aux
	pdflatex $(DOCUMENT).tex
	pdflatex $(DOCUMENT).tex

clean :
	rm -f *.aux *.bbl *.log *.out *.toc *.blg *~ math-cs.pdf *.dvi

