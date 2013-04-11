TARGET = baltagmoss.pdf

$(TARGET): baltagmoss.tex
	pdflatex baltagmoss.tex
# bibtex baltagmoss.aux
#	pdflatex baltagmoss.tex
#	pdflatex baltagmoss.tex

clean:
	rm baltagmoss.pdf baltagmoss.aux
	mv baltagmoss.log baltagmoss_old.log
