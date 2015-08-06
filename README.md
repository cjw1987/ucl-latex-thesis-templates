# UCL LaTeX Thesis Templates

[![Build Status](https://travis-ci.org/UCL/ucl-latex-thesis-templates.svg?branch=master)](https://travis-ci.org/UCL/ucl-latex-thesis-templates)

This is a skeletal thesis template with a class and .sty file that you can use separately if you'd prefer.

The class needs some updating and could use a lot of commenting, and these are being worked on, but the files are perfectly usable right now with pdfLaTeX or lualatex. The repo is tested after each push with lualatex on Travis.

If you have suggestions for improvements, please do submit an issue, drop me a line ([i.kirker@ucl.ac.uk](mailto:i.kirker@ucl.ac.uk)), or throw me a pull request.

*@ikirker*

## Known Issues

#### Citation Links
If you see this error while compiling:

```
pdfTeX warning (dest): name{cite.whatever} has been referenced but does not exist, replaced by a fixed one
```

and then get links that don't work in the PDF, try un-commenting the line below in `MainPackages.tex` even if you don't use that style of citation.

```latex
\usepackage{natbib}
```
