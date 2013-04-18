TARGET = bek2006.pdf

$(TARGET): bek2006.tex
	pdflatex bek2006.tex
# bibtex bek2006.aux
#	pdflatex bek2006.tex
#	pdflatex bek2006.tex

clean:
	rm bek2006.pdf bek2006.aux
	mv bek2006.log bek2006_old.log
