
# Convert all files in this directory that have a .md suffix
SOURCE_DOCS := $(wildcard *.md)

EXPORTED_DOCS=\
 $(SOURCE_DOCS:.md=.pdf)

RM=/bin/rm

PANDOC=pandoc

PANDOC_OPTIONS=--smart --standalone

%.pdf : %.md
	$(PANDOC) $(PANDOC_OPTIONS) $(PANDOC_PDF_OPTIONS) -o $@ $<

.PHONY: all clean


# Targets and dependencies

all : $(EXPORTED_DOCS)

clean:
	- $(RM) $(EXPORTED_DOCS)
