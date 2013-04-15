TARGET = bms1998.pdf

$(TARGET): bms1998.tex
	pdflatex bms1998.tex
# bibtex bms1998.aux
#	pdflatex bms1998.tex
#	pdflatex bms1998.tex

clean:
	rm bms1998.pdf bms1998.aux
	mv bms1998.log bms1998_old.log
