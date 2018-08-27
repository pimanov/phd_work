all: 
	pdflatex autoref.tex

re: clean
	pdflatex autoref.tex
	bibtex autoref.aux
	pdflatex autoref.tex
	pdflatex autoref.tex


clean:
	rm -f *.aux *.log *.bbl *.blg *.toc *.out
