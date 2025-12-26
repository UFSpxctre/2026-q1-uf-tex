.PHONY: all parse clean

parse:
	pdflatex *.tex -halt-on-error
	zathura *.pdf

clean:
	rm -f *.aux *.log *.out *.pdf
