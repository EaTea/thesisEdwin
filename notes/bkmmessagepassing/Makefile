TARGET = bkmmp.pdf

$(TARGET): bkmmp.tex
	pdflatex bkmmp.tex
# bibtex bkmmp.aux
#	pdflatex bkmmp.tex
#	pdflatex bkmmp.tex

clean:
	rm bkmmp.pdf bkmmp.aux
	mv bkmmp.log bkmmp_old.log
