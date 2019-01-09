#BZ's Notes on the Templates

##Template Analysis

###Undocumented Template Files

* `bookzh.sty`\*
* `bstutf8.bst`
  * bibliography style file
* `nomencl.ist`\*\*
  * nomenclature's template (?)
* `nudtx.sty`
  * Necessary for "make cls"
* `slashbox.sty`
  * Is used to create a slash in a cell of tables
* `svgreek.sty`\*
  * Seems not necessary at the moment

###Documented Template Files

* `mynudt.sty`
* `nudtpaper.cfg`
* `nudtpaper.cls`
* `nudtpaper.dtx`
* `nudtpaper.ins`

###Thesis Files

* `thesis.tex`
* `ref/refs.bib`
  * Included in main tex: `\bibliography{ref/refs}`
* `data/*.tex`
  * frontmatter
    * table of contents
    * list of tables
    * list of figures
  * midmatter
    * `abstract.tex`
    * denotation
  * mainmatter
    * `chap01.tex`
    * `chap02.tex`
    * `ack.tex`
    * bibliography
    * `resume.tex`
  * backmatter
    * `appendix01.tex`
* `figures/*`
  * Default graphic path
  * Set by `\graphicspath{{figures/}}`

###Project Management Files

* `makecls.b__`
* `makefile`
* `makepdf.bat`
* `a3cover/makecover.bat`

###Other Files

* a3cover/\*.tex

