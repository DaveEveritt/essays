
simple pdf:

(pandoc iching-essay.md -f markdown --pdf-engine=xelatex -o ichingTEST.pdf) 


but better to use:

pandoc iching-essay.md -f markdown+footnotes -t latex --wrap=none --top-level-division=chapter -s -o ichingNEW.tex

and then:

xelatex ichingNEW
