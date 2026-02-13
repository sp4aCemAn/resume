OUTPUTDIR = ..
FILENAME = resumeTexv1

.PHONY: build clean

build:
	pdflatex $(FILENAME).tex
	mv $(FILENAME).pdf $(OUTPUTDIR)/

clean:
	rm -f *.aux *.log *.out $(OUTPUTDIR)/$(FILENAME).pdf
