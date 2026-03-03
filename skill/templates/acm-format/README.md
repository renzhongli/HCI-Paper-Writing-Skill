# ACM Paper Styles (CHI, UIST, CSCW, DIS)

This directory contains the latest LaTeX templates for ACM SIGCHI conferences.

## Instructions for authors

Paper submissions to CHI, UIST, CSCW, DIS conferences must use the official ACM style templates.

The LaTeX style files are available:

- as an [Overleaf template](https://www.overleaf.com/latex/templates/acm-primary-article-template/pxjhdcxbwppk)
- in this repository
- from [ACM GitHub](https://github.com/borisveytsman/acmart)

Please see [`sample-sigconf.tex`](sample-sigconf.tex) for an example.

Please follow the paper formatting guidelines for ACM conferences:

- [ACM Paper Formatting Guidelines](https://www.acm.org/publications/authors/submission-templates)

Authors may not modify these style files or use templates designed for other conferences.

## Key Files

- `acmart.cls` - Main style file
- `ACM-Reference-Format.bst` - Bibliography style
- `sample-sigconf.tex` - Example document

## Page Limits

- **CHI**: 10 pages (references excluded)
- **UIST**: 10 pages (references excluded)
- **CSCW**: 10 pages (references excluded)
- **DIS**: 10 pages (references excluded)

## Quick Start

```latex
\documentclass[sigconf]{acmart}

\begin{document}
\title{Your Paper Title}
\author{Author Name}
\affiliation{%
  \institution{Your Institution}
  \city{City}
  \country{Country}
}
\email{author@example.com}

\begin{abstract}
Your abstract here.
\end{abstract}

\maketitle

\section{Introduction}
Your content here.

\bibliographystyle{ACM-Reference-Format}
\bibliography{references}
\end{document}
```

## Options

- For review: `\documentclass[sigconf, review]{acmart}` (adds line numbers)
- For camera-ready: `\documentclass[sigconf]{acmart}`

## Compiling

```bash
pdflatex sample-sigconf.tex
bibtex sample-sigconf
pdflatex sample-sigconf.tex
pdflatex sample-sigconf.tex
```
