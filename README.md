# Formal Point of View
Formal Point of View - Webpage resources

Formal Point of View is both a book and a website.

You can compile the book (one-sided) as follows:

```pdflatex mainonesidebooka4.tex```

This will generate the file `mainonesidebooka4.pdf`.

You can compile the book (two-sided, only used for printing book form) with pdflatex as follows:

```pdflatex maintwosidebooka4.tex```

This will generate the file `maintwosidebooka4.pdf`.

You can compile the website with pandoc using:

```pandoc -s --mathjax --toc -c site/style.css mainwebsite.tex -o site/index.html```
