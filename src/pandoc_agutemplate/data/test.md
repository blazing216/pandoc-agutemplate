---
journal: AGU journals
title: Pandoc template for AGU journals
author: Yihe Xu$^{1}$
institute:
  - Bullard Laboratories, Department of Earth Sciences, University of Cambridge
  - Geophysics Section, School of Cosmic Physics, Dublin Institute for Advanced Studies
affiliation:
  - id: 1
    name: Bullard Laboratories, Department of Earth Sciences, University of Cambridge
corr_author: Yihe Xu
corr_author_email: yx362@cam.ac.uk
keypoints:
	- Convert Markdown to pdf, modified based on AGU LaTeX template
	- See Makefile for the exact pandoc command
abstract: >
  Convert research papers in Markdown to pdf using pandoc.
  Add bibliography using `bibliography: [my bib file]`

plain_lang: > 
  You can now use Markdown to write papers for AGU journals
acknowledgements: Thank pandoc for providing the possibility.
---
# Introduction

Introduction goes here

# Data and Method

Use the following command to convert: 
```
pandoc test.md \
	--template=agutemplate.tex \
	--pdf-engine=xelatex \
	-o test.pdf
```

## files provided
* agutemplate.tex. Pandoc template
* test.md. Manuscript in Markdown
* agujournal2019.cls. LaTeX template
* trackchanges.sty
* test.pdf. Manuscript in pdf
* Makefile


# Result

# Discussion

# Conclusions


