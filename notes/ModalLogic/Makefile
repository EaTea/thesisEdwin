TARGET = chapterOne.pdf

$(TARGET): chapterOne.tex
	pdflatex chapterOne.tex
	cp -u chapterOne.pdf /university/cits2232/project/chapterOne.pdf

clean:
	rm chapterOne.pdf chapterOne.aux
	mv chapterOne.log chapterOne_old.log
