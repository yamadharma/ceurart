
v0.3.6 / 2020-10-16
==================

  * feat: align code
  * feat: support tilde in url

v0.3.5 / 2020-10-09
==================

  * feat(template): change overleaf template link
  * feat: add desription in README

v0.3.4 / 2020-10-08
==================

  * feat: revert to latex3 bools
  * feat: add information about the CAS Bundle

v0.3.3 / 2020-08-11
==================

  * feat: add ht option to sample files
  * fix: TeXlive-2019 (Overleaf) issue (#1)

v0.3.2 / 2020-07-10
==================

  * Changed: removed colon in header after short authors names
  * Added: check if abstract exist
  * Added: checked orcid availability
  * Changed: header and foofter format
  * Added: firstpage to PDF/A
  * Added: Lastpage to PDF/A. Need additional LaTeX run
  * Added: option for documentclass to enable header and footer
  * Changed: moved header-footer to KOMA-Script native interface
  * Changed: moved header-footer to fancyhdr package
  * Added: header, shorttitle
  * Added: Footnote with short authors list
  * Changed: cas -> ceur
  * Changed: cas -> ceur
  * Added: \no_break_space: to \firstname to prevent name wrapping on another line
  * Changed: code format
  * Changed: made narrowed itemize line spacing
  * Added: thin spacing in authors short name (eadname)
  * Added: compatibility with latex2e float options
  * Changed: cas -> ceur
  * Changed: removed pdfversion in hypersetup
  * Changed: tuned Makefile
  * Added: pdf linearization in Makefile
  * Changed: optimized .png files
  * Added: link to overleaf template
  * Added: links to online resources

v0.3.1 / 2020-07-01
==================

  * Added: enable microtype
  * Added: set pdf/a-3u version
  * Changed: pdf/a compatible logo
  * Added: \sep delimiter for \Author in .xmpdata file
  * Added: license information to pdf/a
  * Add: ~ as space symbol
  * Changed: set pdf-1.7 by default
  * license
  * Added: CC-BY-SA 4.0 license for word processors files

v0.3.0 / 2020-06-29
==================

  * Added: docx template (thank to Aleksandr Ometov aleksandr.ometov@tuni.fi)

v0.2.10 / 2020-06-29
==================

  * Changed: moved ead[url] -> url option
  * Fixed: DIV for text area size
  * Changed: moved ead -> email option
  * Changed: replaced stm -> ceur in ceurart.cls
  * Old font naming commands for Koma class
  * Fixed keywords box size
  * Fixed list of temporary files in Makefile
  * url added

v0.2.9 / 2020-03-22
=============

  * Removed natbib sort&compress (this is online publication). 
  * Fixed entries' types in bib-file.
  * Restored fontencoding T1 for pdflatex
  * Removed some hyperref warnings
  * Copyright info disabled in PDF/X
  * Check version of fontawesome5.sty (needs for orcid icon)
  * PDF/X preliminary support

v0.2.8 / 2020-03-21
=============

  * symlinks -> files

v0.2.7 / 2020-03-21
=============

  * User template directory

v0.2.6 / 2020-03-21
=============

  * Sample maked consistent with class
  * conference command changed
  * Moved bibstyle stuff to class
  * Switched to libertinus fonts

v0.2.5 / 2020-03-11
=============

  * Workaround for bibstyle elsarticle-num-names.bst absence
  * Check stix and stix2 fonts

v0.2.4 / 2020-03-11
==================

  * Added workaround for fontawesome5.sty absence

v0.2.3 / 2020-03-10
===================

  * Abstract box indentation
  * sffamily for Abstract and Keywords words
  * Fonts: rm: liberation, sf: biolinum, tt: inconsolata, math: stix2
  * 1col fontsize=11pt, 2col fontsize=10pt, DIV=12
  * Cropped ceur-ws logo

v0.2.2 / 2020-03-08
===================

  * README
  * licence
  * Initial commit
