# PhDtemplate
 A LaTeX template for an article based PhD.
 
# Compile settings

pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex|bibtex introduction.aux|bibtex PaperI.aux|bibtex PaperII.aux|bibtex PaperIII.aux|bibtex PaperIV.aux|bibtex addendum.aux|bibtex appendices.aux|pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex|pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex

