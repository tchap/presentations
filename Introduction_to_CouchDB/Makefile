BASENAME := Introduction_to_CouchDB

%.pdf: %.tex
	pdflatex $<

all: ${BASENAME}.pdf

sections: ${BASENAME}.pdf
	@touch ${BASENAME}.tex
	@make

clean:
	$(RM) *.aux *.log *.nav *.out *.pdf *.snm *.toc *.vrb
