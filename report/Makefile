.PHONY: typeset

FILES=`cat index.txt`

typeset:
	pandoc                        \
	  --from         markdown     \
	  --to           latex        \
	  --template     template.tex \
	  --out          report.pdf   \
	  --latex-engine xelatex      \
	  $(FILES)
