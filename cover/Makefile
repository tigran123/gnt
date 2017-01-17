all:	gnt-spine.pdf gnt-front.pdf gnt-cover.pdf

.PHONY:		clean

clean:		
		@rm -f *.{log,aux}

vclean:		clean
		@rm -f *.dvi *.pdf

%.pdf:	%.tex
	pdflatex $<
