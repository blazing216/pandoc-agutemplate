
# pandoc-agutemplate

`test.md`

````markdown
---
journal: AGU journals
title: Pandoc template for AGU journals
author: Yihe Xu$^{1}$
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
  md2agu test.md
```

## files provided

Inside the directory `src/pandoc_agutemplate/data`
* agutemplate.tex. Pandoc template
* test.md. Manuscript in Markdown
* agujournal2019.cls. LaTeX template
* trackchanges.sty
* agu-docx.tex. Pandoc template for Word
* agu-reference.docx. Word template


# Result

# Discussion

# Conclusions

````

## PDF generated
![image](https://user-images.githubusercontent.com/19185367/147004792-f8c830a2-d84f-4b7d-aa87-58cbc5808101.png)

## Docx generated
![image](https://user-images.githubusercontent.com/19185367/147004935-24ba4616-8ccb-432b-aef3-3c8cea4e9ae1.png)

