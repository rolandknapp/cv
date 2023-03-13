# CV
This repository contains the source files to build my CV, using Quarto and LATEX. The use of Quarto and Latex provided the design flexibility that I found lacking in alternative approaches (e.g., [vitae](https://github.com/ropenscilabs/vitae) package). Instead of including lots of LATEX, it would be best to format the CV using a template. That might be a next step. 

The `.bib` file contains references for my scientific publications, and was exported from a [Zotero](https://www.zotero.org) library. Using Zotero defaults for exporting `.bib` files, the file contained numerous unnecessary fields (copyright, issn, abstract, month, file, keywords, pmid). These were stripped using [Biblatex-Field-Stripper](https://github.com/JakeC007/Biblatex-Field-Stripper), with strip.py run using [replit](https://replit.com/).

The ecology citation style (`ecology.csl`) was edited to sort references by year-author, and add reference numbers (`ecology_edited.csl`: lines 172-175, 177). 