.PHONY: all
all:
	$(info ==> Generating the PDF in JDF-2.0.)
	pdflatex main
	bibtex main
	python enumerate-refs.py
	pdflatex main
	pdflatex main
