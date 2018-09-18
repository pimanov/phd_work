all: 
	pdflatex autoref.tex

re: clean
	pdflatex autoref.tex
	biber autoref
	pdflatex autoref.tex


clean:
	rm -f *.aux *.log *.bbl *.blg *.toc *.out
