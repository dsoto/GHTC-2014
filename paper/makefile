# makefile needs to
# convert md to tex
# use ieee latex template
# compile pdf
# handle plot and figure dependencies

handle=paper

all: $(handle).pdf preprint.pdf

$(handle).pdf: $(handle).md charging-returns.pdf general-returns.pdf
	pandoc --template soto-latex-ghtc.tex -o $(handle).pdf $(handle).md

charging-returns.pdf: ../calculations/charging-returns.ipynb
	runipy ../calculations/charging-returns.ipynb
	#mv charging-returns.pdf ../calculations/

general-returns.pdf: ../calculations/general-returns.ipynb
	runipy ../calculations/general-returns.ipynb

tex:
	pandoc --template soto-latex-ghtc.tex -o $(handle).tex $(handle).md

preprint.pdf: $(handle).pdf
	pandoc --template soto-preprint.tex -o preprint.pdf $(handle).md

# clean:
# 	rm presentation.pdf presentation.tex *.log *.aux
