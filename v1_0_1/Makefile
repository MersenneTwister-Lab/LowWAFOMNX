PANDOC = pandoc
PANDOCFLAGS = --self-contained -t html5 -c $(HOME)/.pandoc/github.css

all: lowWAFOMSobol-ja.html

%.html:%.md
	$(PANDOC) $(PANDOCFLAGS) -o $@ $<

#%.html:%.Rd
#	$(PANDOC) $(PANDOCFLAGS) -o $@ $<

lowWAFOMNX-ja.html:lowWAFOMNX-ja.Rmd
	Rscript -e "rmarkdown::render('lowWAFOMNX-ja.Rmd')"
