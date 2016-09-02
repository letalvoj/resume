DOCUMENT=resume

all: clean
	pdflatex $(DOCUMENT)
	bibtex $(DOCUMENT)
	pdflatex $(DOCUMENT)

clean:
	rm $(DOCUMENT).aux $(DOCUMENT).bbl $(DOCUMENT).blg $(DOCUMENT).log || echo nothing to remove
