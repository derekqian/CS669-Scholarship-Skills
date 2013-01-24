all:
	latex summary
	bibtex summary
	latex summary
	latex summary
	dvips summary
	ps2pdf summary.ps

clean:
	rm -f *.blg
	rm -f *.bbl
	rm -f *.log
	rm -f *.aux
	rm -f *.dvi
	rm -f *.ps
	rm -f *.pdf