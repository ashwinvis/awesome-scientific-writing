# Awesome Scientific Writing [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

> Scientific writing can extend beyond LaTeX, made possible by formats,
> such as
> [Markdown](https://commonmark.org/) (and its many flavours),
> [reStructuredText](https://docutils.sourceforge.io/docs/ref/rst/directives.html) and
> [Jupyter notebooks](https://jupyter.readthedocs.io/en/latest/).

:bookmark: means ability to **seamlessly cite references**.<br/>
:link: means ability to **cross-reference figures and sections within the
document**.<br/>

## Contents

- [Word Processors](#word-processors)
- [Bibliography](#bibliography)
- [Illustrations](#illustrations)
- [Extras](#extras)
- [Spell Checking](#spell-checking)
- [Linters](#linters)
- [Templates](#templates)
  - [Articles](#articles)
  - [Presentations](#presentations)
- [Tutorials](#demos)
- [Other Awesome Lists](#other-awesome-lists)

## Word Processors
Word Processors which can generate LaTeX, HTML or PDF output on demand.

- [academicmarkdown](https://github.com/smathot/academicmarkdown#readme) - A
   Python wrapper over Pandoc with specialized extensions to parse certain
   elements, making it a superset of Pandoc markdown flavour :bookmark:
   :link:.
- [bookbook](https://github.com/takluyver/bookbook/#readme) - An experimental Python
   package which extends `nbconvert` and adds the ability to cross reference
   within and across notebooks :link:.
- [bookdown](https://github.com/rstudio/bookdown/#readme) - R package to facilitate
   writing books and long-form articles/reports with R Markdown :bookmark:
   :link:.
- [Cicero](https://cicero.xyz/) - Python package which renders HTML presentations
   from markdown source using remark or reveal.js :link:.
- [docutils](https://docutils.sourceforge.io/docs/) - Python package which can
   convert reStructuredText into various formats and provides command-line
   tools to do it :link:.
- [ipypublish](https://github.com/chrisjsewell/ipypublish/#readme) - A workflow for
   creating and editing publication ready scientific reports and presentations,
   from one or more Jupyter Notebooks, without leaving the browser! :bookmark:
   :link:.
- [markdeep](https://casual-effects.com/markdeep/) - Markdeep is a JS library
   which supports a variety of content as extensions of Markdown syntax
   :bookmark: :link:.
- [nbconvert](https://nbconvert.readthedocs.io/en/latest/) - Convert Jupyter
   notebooks into `reveal.js` presentations, PDF, HTML, Markdown,
   reStructuredText and more.
- [org-mode](https://orgmode.org) - Powerful Emacs package for authoring notes,
   TODO lists, spreadsheets, documents, executable code-blocks and a lot more
   in a plain text format called Org :bookmark: :link:.
- [pandoc](https://pandoc.org/MANUAL) - A Haskell library for converting from
   one markup format to another, and a command-line tool that uses this
   library :bookmark: :link:.
- [Zettlr](https://www.zettlr.com/) - An electron based markdown editor which
   integrates Zotero, pandoc and many more features wrapped in an elegant WYSIWYG
   interface :bookmark: :link:.

## Bibliography
Bibliography managers to generate citations / BibTeX / BibLaTeX files.

- [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/) - Enhanced
 exporting tool for Zotero.
- [Citation Style Language (CSL) styles](https://editor.citationstyles.org/) -  A
 crowdsourced repository with over 9000 free CSL citation styles and an online
 editor to create new ones.
- [fzf-bibtex](https://github.com/msprev/fzf-bibtex/#readme) - A BibTeX source
 with vim integration which uses fzf (a fuzzy finder implemented in Go).
- [Zotero](https://www.zotero.org/) - FOSS tool to collect, organize, cite, and
 share research.

## Illustrations
Drawing illustrations themselves has driven many a scientist mad. Fortunately,
there are formal languages with which one can create beautiful graphics.

- [diagrams.net](https://www.diagrams.net/) - Open source, online, desktop and
 container deployable diagramming software
- [graphviz](https://graphviz.org/) - Visualization software for graphs and
 networks which uses a domain-specific DOT language.

## Extras
Supplementary files and tools.

- [Pandoc filters](https://github.com/jgm/pandoc/wiki/Pandoc-Filters) - List of
 addons to pandoc which implement extra features such as citations and
 cross-references.
- [Panflute](http://scorreia.com/software/panflute/) - A pythonic alternative
 to John MacFarlane's pandocfilters.
- [vim-pandoc](https://github.com/vim-pandoc/vim-pandoc/#readme) - Pandoc
 integration and utilities for Vim.
- [vim-pandoc-syntax](https://github.com/vim-pandoc/vim-pandoc-syntax/#readme) - Lightweight
 rendering of pandoc syntax in Vim.

## Spell Checking
Check spelling.

## Linters
Check grammar and language.

- [LanguageTool](https://languagetool.org/) - Open source grammar, style and
 spell Checker.
- [proselint](http://proselint.com/) - A linter for prose.
- [textlint](https://textlint.github.io/) - The pluggable linting tool for text
 and markdown.
- [textidote](https://sylvainhalle.github.io/textidote/) - Spelling, grammar and
 style checking on LaTeX documents.
- [Vale](https://errata-ai.github.io/vale/) - A free, open-source linter for
 prose built with speed and extensibility in mind.
- [write-good](https://github.com/btford/write-good) - Naive linter for English
 prose.

## Templates
Reusable minimalistic examples.

### Articles

- [Pandoc Markdown-Latex
   Boilerplate](https://github.com/davecap/markdown-latex-boilerplate/#readme) - Demonstrate
   how to integrate Pandoc with an existing LaTeX template which
   requires some boilerplate code (i.e. LaTeX preamble), thus avoiding the
   `latexmk` dependency.
- [scientific-markdown](https://github.com/JensErat/scientific-markdown/#readme) - Example
   for use of Markdown for scientific publications using Pandoc and
   `latexmk` :star:.

### Presentations

- [pandoc-starter](https://github.com/jez/pandoc-starter/#readme) - Templates for
   articles, beamer presentations etc. using Markdown files and Makefiles for
   getting started with Pandoc.
- [slides](https://github.com/cgroll/slides/#readme) - Demo for generating `reveal.js`
   presentations using Pandoc.

### Books

- [bookdown-demo](https://github.com/rstudio/bookdown-demo/#readme) - Minimal
   example of a book based on R Markdown and bookdown.
- [markdeep-thesis](https://github.com/doersino/markdeep-thesis#readme) - Write
   your (under)graduate thesis with Markdeep and typeset it right in your
   browser.
- [Template for writing a PhD thesis in
   Markdown](https://github.com/tompollard/phd_thesis_markdown#readme) - A clean
   organization of files to provide a framework for writing a PhD thesis in
   mostly Markdown with a little bit of LaTeX, and compiled with Pandoc.

## Tutorials
How to generate articles and presentations for scientific purposes.

- [Book on Riemann solvers](https://github.com/clawpack/riemann_book/#readme) - This
   example uses a custom `nbconvert` template and shows how to store your
   notebooks with no output (for version control) while automatically executing
   them before running `bookbook`, so that PDF and HTML versions include the
   output.
- [Katrin Leinweber's Ph.D.
   thesis](https://github.com/katrinleinweber/PhD-thesis/#readme) - Automated
   work flow involving several tools, but primarily Pandoc, `latexmk` and
   AcademicMarkdown.
- [Teaching and learning with
   Jupyter](https://github.com/jupyter4edu/jupyter-edu-book/#readme) - Book
   written in R Markdown, bookdown and also rendered as HTML, PDF and
   EPUB.
- [Writing scientific papers for ACPD using Emacs
   Org-mode](https://www.draketo.de/english/emacs/writing-papers-in-org-mode-acpd) - Detailed
   tutorial on authoring a paper by seamlessly integrating with LaTeX
   commands within Org-mode.

## Other Awesome Lists
- [Jupyter](https://github.com/markusschanta/awesome-jupyter/#renderingpublishingconversion)
- [LaTeX](https://github.com/egeerardyn/awesome-LaTeX/#readme)
- [Markdown](https://github.com/BubuAnabelas/awesome-markdown/#readme)

## Contribute
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Ashwin Vishnu has waived all copyright
and related or neighbouring rights to this work. See [LICENSE](LICENSE).

