TARGET = review.pdf

$(TARGET): review.tex litReview.bib
	pdflatex review.tex
	bibtex review.aux
	pdflatex review.tex
	pdflatex review.tex

clean:
	rm review.pdf review.aux
	mv review.log review_old.log
