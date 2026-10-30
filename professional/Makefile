
MAIN = cv

all: $(MAIN).pdf


$(MAIN).pdf: $(MAIN).tex cv.bib
	@latexmk -pdf $(@:.pdf=.tex)


clean:
	@latexmk -c
	@rm -f $(MAIN).pdf *.bak *.bbl *.run.xml ./sections/*.bak

.PHONY: all clean
