.PHONY: all parse clean

parse:
	pdflatex *.tex -halt-on-error
	../open-pdf

clean:
	rm -f *.aux *.log *.out *.pdf
