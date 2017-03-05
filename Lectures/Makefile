PANDOC = pandoc
IFORMAT = markdown+latex_macros
FLAGS = -s -t beamer --slide-level 3 --include-in-header macros.md
TEMPLATE = page.tmpl
STYLE = css/style.css

HTML = tutorial.html

00:
	$(PANDOC) -f $(IFORMAT) $(FLAGS) -o 00_Introduction.pdf slides_header.md 00_Introduction.md

01:
	$(PANDOC) -f $(IFORMAT) $(FLAGS) -o 01_DiscreteInformationSources.pdf slides_header.md 01_DiscreteInformationSources.md

01w: 01
	start 01_DiscreteInformationSources.pdf &
	
02:
	$(PANDOC) -f $(IFORMAT) $(FLAGS) -o 02_DiscreteTransmissionChannels.pdf slides_header.md 02_DiscreteTransmissionChannels.md

02w: 02
	start 02_DiscreteTransmissionChannels.pdf &
