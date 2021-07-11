# LaTeX user template and guide

## List of files

### Sample files using `listings` package

  * sample-1col.tex: One column
  * sample-2col.tex: Two columns

### Sample files using `minted` package

  * sample-1col+minted.tex: One column
  * sample-2col+minted.tex: Two columns

These files need `pygment` executable:
  *  <http://pygments.org/>;
  *  <http://pypi.python.org/pypi/Pygments>.

## How to compile

To compile user guide:

1. `pdflatex sample-1col`
2. `bibtex sample-1col`
3. `pdflatex sample-1col`
4. `pdflatex sample-1col`

and

1. `pdflatex sample-2col`
2. `bibtex sample-2col`
3. `pdflatex sample-2col`
4. `pdflatex sample-2col`

or

use the makefile:

`make`

