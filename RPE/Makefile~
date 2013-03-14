all:
	latex paper
	bibtex paper
	latex paper
	latex paper
	dvips paper
	ps2pdf paper.ps

clean:
	rm -f paper.log
	rm -f paper.aux
	rm -f paper.dvi
	rm -f paper.ps
	rm -f paper.pdf
