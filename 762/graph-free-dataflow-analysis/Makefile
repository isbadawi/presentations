slides.pdf: slides.tex bib.bib
	pdflatex slides.tex
	bibtex slides
	pdflatex slides.tex
	pdflatex slides.tex

clean:
	rm *.aux *.bbl *.blg *.log *.nav *.out *.snm *.toc *.vrb *.pdf
