OUTPUTDIR = ..
FILENAME = resumeTexv1

.PHONY: build clean publish

build:
	pdflatex $(FILENAME).tex

clean:
	rm -f *.aux *.log *.out *.pdf

publish:
		cp $(FILENAME).pdf $(OUTPUTDIR)/$(FILENAME).pdf


