.PHONY: SSPUThesis.pdf clean-nt clean-unix ./SSPUBeamer.pdf

SSPUThesis.pdf: SSPUThesis.tex bibdatabase.bib
	xelatex -synctex=1 -interaction=nonstopmode -file-line-error -pdf SSPUThesis.tex
	bibtex SSPUThesis
	xelatex -synctex=1 -interaction=nonstopmode -file-line-error -pdf SSPUThesis.tex
	xelatex -synctex=1 -interaction=nonstopmode -file-line-error -pdf SSPUThesis.tex

clean-unix:
	rm *.aux
	rm *.bbl
	rm *.blg
	rm *.log
	rm *.out
	rm *.gz
	rm *.toc

clean-nt:
	del *.aux
	del *.bbl
	del *.blg
	del *.log
	del *.out
	del *.gz
	del *.toc
