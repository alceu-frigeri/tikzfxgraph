tikzfxgraph
==========


Plotting functions in a simplified way.
(using pgfplots and gnuplot)

For more details,  see the documentation,
[tikzfxgraph.pdf](http://mirrors.ctan.org/graphics/pgf/contrib/tikzfxgraph/doc/tikzfxgraph.pdf)
	
--------------

## Requirements
* a fairly recent LaTeX distribution as recent as 2022/06/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand*).
* gnuplots version 5.4 recommended (version 6 works, but generate some character error messages, due to a UTF8/UTF16 mismatch) 

## Installation
The stable version is available at [CTAN](https://ctan.org/pkg/tikzfxgraph).

## Usage
### Stable version
Just place
```latex
  \usepackage{tikz}
  \usepackage{pgfplots}
  ...
  \usepackage{tikzfxgraph}
```

in the preamble and compile away.

## Contacting Author

For bug reports and enhancement suggestions, the preferred way is to use
[the project's issue page](https://github.com/alceu-frigeri/tikzfxgraph/issues).
Please be ready to provide an example code showing the bug, if any.

Please do not use the issue page for generic help on how to use the package.

* git: https://github.com/alceu-frigeri/tikzfxgraph

-------------
Copyright 2025-present by Alceu Frigeri

 This work may be distributed and/or modified under the
 conditions of

 * The [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), version 1.3c (or later), and/or
 * The [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), version 3 (or later)

This work has the LPPL maintenance status *maintained*.

The Current Maintainer of this work is Alceu Frigeri

-------------
## This work consist of the files

* tikzfxgraph.sty
    - the package itself

* README.md  (this file)
    - quick introduction

* tikzfxgraph.bib
* tikzfxgraph.tex
    - package documentation
* tikzfxgraph.pdf
    - documentation in PDF format
    
-------------

## Change log
* Version 1.1 (this)
    - new package options:
      - (to) suppress some warnings, 
      - (to) change the default number of samples
      - (to) allow the use of pre-calculated tables instead of calling gnuplot (pgf/pgfplots work around)
    
* Version 1.0a
    - switching over pkginfograb package's info
    - no longer using any kernel scratch variable.

* Version 1.0
    - Initial setup.
    - Initial CTAN release.
