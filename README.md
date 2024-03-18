# PhD thesis template for R markdown

The file ThesisTemplate.Rmd is an R markdown file that provides a template to write a PhD thesis following the University of York formatting guidelines (https://www.york.ac.uk/research/graduate-school/progression/thesis/format/). The file includes comments and examples to help the user to format their thesis.

The ThesisTemplate.pdf file is an example of the file that is created by knitting the markdown file in R studio.

The referencesThesis.bib is the file where all the references will be collected and that will be used by the markdown file to create citations in the text and to compile the reference list.

The elife.csl is the file that defines the citation style that will be used in the thesis. Different csl files for different citation style can be found on Zotero (https://www.zotero.org/styles).

Before knitting the document for the first time, if you want to create PDF documents from R Markdown, you will need to have a LaTex distribution installed. You can install TinyTeX with the R package tinytex: tinytex::install_tinytex()
