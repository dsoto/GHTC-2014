# makefile for GHTC 2014 submission

handle=paper
calcs=../calculations

all: $(handle).pdf preprint.pdf $(handle).html

$(handle).pdf: $(handle).md charging-returns.pdf general-returns.pdf
	pandoc --template soto-latex-ghtc.tex -o $(handle).pdf $(handle).md

charging-returns.pdf: $(calcs)/charging-returns.ipynb
	runipy $(calcs)/charging-returns.ipynb

general-returns.pdf: $(calcs)/general-returns.ipynb
	runipy $(calcs)/general-returns.ipynb

tex:
	pandoc --template soto-latex-ghtc.tex -o $(handle).tex $(handle).md

preprint.pdf: $(handle).pdf
	pandoc --template soto-preprint.tex -o preprint.pdf $(handle).md

$(handle).html: $(handle).pdf
	pandoc --template soto-template.html -o $(handle).html $(handle).md
