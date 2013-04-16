TARGET = presentation.pdf

$(TARGET): presentation.tex
	pdflatex presentation.tex
# bibtex presentation.aux
#	pdflatex presentation.tex
#	pdflatex presentation.tex

clean:
	rm presentation.pdf presentation.aux
	mv presentation.log presentation_old.log
