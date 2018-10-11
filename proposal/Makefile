pdf:
	@TEXINPUTS=.//: pdflatex -synctex=1 -interaction=nonstopmode --shell-escape main
all:
	@TEXINPUTS=.//: pdflatex -synctex=1 -interaction=nonstopmode --shell-escape main
	bibtex main
	pdflatex -synctex=1 -interaction=nonstopmode  --shell-escape main
	pdflatex -synctex=1 -interaction=nonstopmode  --shell-escape main
clean:
	find . -type f \( -name  '*.cut' -or -name  '*.bcf' -or -name  '*.xcp' -or -name  '*.thm' -or -name  '*.xml' -or -name '*.aux' -or -name  '*.auxlock' -or -name '*.figlist' -or -name '*eps-converted-to.pdf' -or -name '*.bbl' -or -name '*.fdb_latexmk' -or -name '*.synctex.gz' -or -name '*.blg' -or -name '*.log' -or -name '*.out' -or -name '*.toc' -or -name '*.lot' -or -name '*.lof' -or -name '*.loa' -or -name '*.fls' \) -exec rm -f '{}' \;

