# makefile for GHTC 2014 submission


# handle plots as a list?

handle=paper
calcs=../calculations
templates=../templates

all: $(handle).pdf $(handle)-preprint.pdf $(handle).html $(handle).docx

$(handle).pdf: $(handle).md charging-returns.pdf general-returns.pdf
	pandoc --filter pandoc-citeproc --csl=ieee.csl --bibliography=$(handle).bib --template $(templates)/soto-latex-ghtc.tex -o $(handle).pdf $(handle).md

charging-returns.pdf: $(calcs)/charging-returns.ipynb
	runipy $(calcs)/charging-returns.ipynb

general-returns.pdf: $(calcs)/general-returns.ipynb
	runipy $(calcs)/general-returns.ipynb

tex:
	pandoc --template $(templates)/soto-latex-ghtc.tex -o $(handle).tex $(handle).md

$(handle)-preprint.pdf: $(handle).pdf
	pandoc --filter pandoc-citeproc --csl=ieee.csl --bibliography=$(handle).bib --template $(templates)/soto-preprint.tex -o $(handle)-preprint.pdf $(handle).md

$(handle).html: $(handle).pdf
	pandoc --template $(templates)/soto-template.html -N --css=../css/soto.css -o $(handle).html $(handle).md

$(handle).docx: $(handle).pdf
	pandoc --filter pandoc-citeproc --csl=ieee.csl --bibliography=$(handle).bib -o $(handle).docx $(handle).md
