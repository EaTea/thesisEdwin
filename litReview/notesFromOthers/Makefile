TARGET = notes.pdf

$(TARGET): notes.tex
	pdflatex notes.tex
# bibtex notes.aux
#	pdflatex notes.tex
#	pdflatex notes.tex

clean:
	rm notes.pdf notes.aux
	mv notes.log notes_old.log
