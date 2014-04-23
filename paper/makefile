# makefile needs to
# convert md to tex
# use ieee latex template
# compile pdf
# handle plot and figure dependencies

handle=paper

pdf:
	#pandoc --template soto-paper.tex -o $(handle).pdf $(handle).md
	pandoc --template soto-latex.tex -o $(handle).pdf $(handle).md

# tex:
# 	pandoc -t beamer --template soto-beamer.tex -o presentation.tex presentation.md
# 	pdflatex presentation.tex
#
# clean:
# 	rm presentation.pdf presentation.tex *.log *.aux
