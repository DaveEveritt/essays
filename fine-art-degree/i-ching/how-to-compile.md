# README

simple pdf:

(pandoc index.md -f markdown --pdf-engine=xelatex -o ichingTEST.pdf) 


but better to use:
AFTER making BACKUP of old file!!

pandoc index.md -f markdown+footnotes -t latex --wrap=none --top-level-division=chapter -s -o iching.tex

and then:

xelatex iching

