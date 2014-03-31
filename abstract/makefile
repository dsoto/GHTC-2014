all:
	#pandoc -o abstract.pdf --template soto-pandoc.tex abstract.md
	pandoc -o abstract.tex --template soto-abstract.tex abstract.md
	pdflatex abstract.tex

tidy:
	rm *.log *.out *.aux

clean:
	make tidy
	rm abstract.pdf abstract.tex
