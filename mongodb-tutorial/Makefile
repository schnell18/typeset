all:    manual

# repeat four times
manual: manual.tex
	lualatex -shell-escape -synctex=1 manual
	lualatex -shell-escape -synctex=1 manual
	lualatex -shell-escape -synctex=1 manual
	lualatex -shell-escape -synctex=1 manual

clean:
	rm -fr *.aux *.log *.nav *.out *.pdf *.snm *.toc *.vrb *.lof *.lot *.lol _minted*
