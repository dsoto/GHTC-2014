# makefile for GHTC 2014 submission


# TODO: how do I handle plots as a list?  this is easier since they all
# come from same file
# TODO: preprocess tex file and convert longtable to tabular or whatever
# will work in two-column mode

handle=paper
calcs=../calculations/ghtc-2014-supplementary.ipynb
templates=../templates

# need to put pdf target back in this list
all: $(handle)-preprint.pdf $(handle).html $(handle).docx tex

#$(handle).pdf: $(handle).md charging-returns.pdf general-returns.pdf
#	pandoc --filter pandoc-citeproc --csl=ieee.csl --bibliography=$(handle).bib --template $(templates)/soto-latex-ghtc.tex -o $(handle).pdf $(handle).md

charging-returns.pdf: $(calcs)
	runipy $(calcs)

general-returns.pdf: $(calcs)
	runipy $(calcs)

monthly-payment.pdf: $(calcs)
	runipy $(calcs)

biab-cost.pdf: $(calcs)
	runipy $(calcs)


preprint-tex:
	pandoc --filter pandoc-citeproc --csl=ieee.csl --bibliography=$(handle).bib --template $(templates)/soto-preprint.tex -o $(handle).tex $(handle).md

tex:
	pandoc --filter pandoc-citeproc --csl=ieee.csl --bibliography=$(handle).bib --template $(templates)/soto-latex-ghtc.tex -o $(handle).tex $(handle).md
	#sed -i bak s/longtable/supertabular/g paper.tex
	#pdflatex $(handle).tex

$(handle)-preprint.pdf: $(handle).md charging-returns.pdf general-returns.pdf monthly-payment.pdf
	pandoc --filter pandoc-citeproc --csl=ieee.csl --bibliography=$(handle).bib --template $(templates)/soto-preprint.tex -o $(handle)-preprint.pdf $(handle).md

$(handle).html: $(handle).md
	pandoc --template $(templates)/soto-template.html -N --css=../css/soto.css -o $(handle).html $(handle).md

$(handle).docx: $(handle).md
	pandoc --filter pandoc-citeproc --csl=ieee.csl --bibliography=$(handle).bib -o $(handle).docx $(handle).md
