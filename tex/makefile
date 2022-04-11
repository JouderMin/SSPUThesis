.PHONY: SSPUThesis.pdf clean ./SSPUBeamer.pdf

SSPUThesis.pdf: SSPUThesis.tex bibdatabase.bib
	xelatex -synctex=1 -interaction=nonstopmode -file-line-error -pdf SSPUThesis.tex
	bibtex SSPUThesis
	xelatex -synctex=1 -interaction=nonstopmode -file-line-error -pdf SSPUThesis.tex
	xelatex -synctex=1 -interaction=nonstopmode -file-line-error -pdf SSPUThesis.tex

clean:
	rm *.aux
	rm *.bbl
	rm *.blg
	rm *.log
	rm *.out
	rm *.gz
	rm *.toc
