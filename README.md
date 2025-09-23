# Essays

Essays I've written over many years on various topics (in contrast to academic papers).

## Contents

- Fine Art Degree essays (early 70s)
  - [The I Ching (Book of Change)](https://daveeveritt.github.io/essays/fine-art-degree/i-ching/) ([code](https://github.com/DaveEveritt/essays/blob/main/fine-art-degree/i-ching/index.md))
  - [From the Personal to the Universal](https://daveeveritt.github.io/essays/fine-art-degree/personal-universal/) ([code](https://github.com/DaveEveritt/essays/blob/main/fine-art-degree/personal-universal/index.md))

- Technology and Culture (2000s)
  - [Cyberspace is the Astral Plane](https://daveeveritt.github.io/essays/technology-and-culture/cyberspace-is-the-astral-plane.html) ([code](https://github.com/DaveEveritt/essays/blob/main/technology-and-culture/cyberspace-is-the-astral-plane.md))
  - [New Media](https://daveeveritt.github.io/essays/technology-and-culture/new-media.html) ([code](https://github.com/DaveEveritt/essays/blob/main/technology-and-culture/new-media.md))

- Science, Psychology, Social
  - [Order, Disorder and the finely Tuned Universe](https://daveeveritt.github.io/essays/science-psychology-social/the-finely-tuned-universe.html) ([code](https://github.com/DaveEveritt/essays/blob/main/science-psychology-social/the-finely-tuned-universe.md))
  - [Purpose and Purposelessness](https://daveeveritt.github.io/essays/science-psychology-social/purpose-and-purposelessness.html) ([code](https://github.com/DaveEveritt/essays/blob/main/science-psychology-social/purpose-and-purposelessness.md))

- Personal Observations
  - [Perception](https://daveeveritt.github.io/essays/personal-observations/perception.html) ([code](https://github.com/DaveEveritt/essays/blob/main/personal-observations/perception.md))
  - [Experience](https://daveeveritt.github.io/essays/personal-observations/experience.html) ([code](https://github.com/DaveEveritt/essays/blob/main/personal-observations/experience.md))

---

## Pandoc compilation:

- `pandoc DOCUMENT_NAME.md -f markdown_mmd+yaml_metadata_block --pdf-engine=pdflatex --top-level-division=chapter -o DOCUMENT_NAME.pdf`
- `pandoc DOCUMENT_NAME.md -f markdown_mmd+yaml_metadata_block --pdf-engine=pdflatex -o DOCUMENT_NAME.pdf`
- simple pdf: `pandoc index.md -f markdown --pdf-engine=xelatex -o OUTPUT_NAME.pdf`

Better example with footnotes, using I Ching essay (AFTER making BACKUP of old file!):

- `pandoc index.md -f markdown+footnotes -t latex --wrap=none --top-level-division=chapter -s -o iching.tex`
- then: `xelatex iching`
