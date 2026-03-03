# LaTeX Templates for HCI/Visualization Conferences

This directory contains instructions for official LaTeX templates for major HCI and visualization conferences.

---

## Compiling LaTeX to PDF

### Option 1: VS Code with LaTeX Workshop (Recommended)

**Setup:**
1. Install [TeX Live](https://www.tug.org/texlive/) (full distribution recommended)
   - macOS: `brew install --cask mactex
   - Ubuntu: `sudo apt install texlive-full
   - Windows: Download from [tug.org/texlive](https://www.tug.org/texlive/)

2. Install VS Code extension: **LaTeX Workshop** by James Yu
   - Open VS Code → Extensions (Cmd/Ctrl+Shift+X) → Search "LaTeX Workshop" → Install

**Usage:**
- Open any `.tex` file in VS Code
- Save the file (Cmd/Ctrl+S) → Auto-compiles to PDF
- Click the green play button or use `Cmd/Ctrl+Alt+B` to build
- View PDF: Click "View LaTeX PDF" icon or `Cmd/Ctrl+Alt+V`
- Side-by-side view: `Cmd/Ctrl+Alt+V` then drag tab

**Settings** (add to VS Code `settings.json`):
```json
{
  "latex-workshop.latex.autoBuild.run": "onSave",
  "latex-workshop.view.pdf.viewer": "tab",
  "latex-workshop.latex.recipes": [
    {
      "name": "pdflatex → bibtex → pdflatex × 2",
      "tools": ["pdflatex", "bibtex", "pdflatex", "pdflatex"]
    }
  ]
}
```

### Option 2: Command Line

```bash
# Basic compilation
pdflatex main.tex

# With bibliography (full workflow)
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex

# Using latexmk (handles dependencies automatically)
latexmk -pdf main.tex

# Continuous compilation (watches for changes)
latexmk -pdf -pvc main.tex
```

### Option 3: Overleaf (Online)

1. Go to [overleaf.com](https://overleaf.com)
2. New Project → Upload Project → Upload the template folder as ZIP
3. Edit online with real-time PDF preview
4. No local installation needed

### Option 4: Other IDEs

| IDE | Extension/Plugin | Notes |
|-----|------------------|-------|
| **Cursor** | LaTeX Workshop | Same as VS Code |
| **Sublime Text** | LaTeXTools | Popular, well-maintained |
| **Vim/Neovim** | VimTeX | Powerful, keyboard-driven |
| **Emacs** | AUCTeX | Comprehensive LaTeX environment |
| **TeXstudio** | Built-in | Dedicated LaTeX IDE |
| **Texmaker** | Built-in | Cross-platform LaTeX editor |

### Troubleshooting Compilation

**"File not found" errors:**
```bash
# Ensure you're in the template directory
cd templates/acm-format
# Then compile
pdflatex your-paper.tex
```

**Bibliography not appearing:**
```bash
# Run bibtex after first pdflatex
pdflatex main.tex
bibtex main        # Uses main.aux to find citations
pdflatex main.tex  # Incorporates bibliography
pdflatex main.tex  # Resolves references
```

**Missing packages:**
```bash
# TeX Live package manager
tlmgr install <package-name>

# Or install full distribution to avoid this
```

---

## Available Templates

| Conference Series | Directory | Format | Source |
|------------|-----------|------|--------|
| **CHI, UIST, CSCW, DIS | `acm-format/` | ACM | [ACM Master Article Template](https://www.overleaf.com/latex/templates/acm-primary-article-template/pxjhdcxbwppk) |
| **IEEE VIS, PacificVis | `ieee-vis/` | IEEE | [IEEE TVCG Template](https://www.overleaf.com/latex/templates/ieee-transactions-on-visualization-and-computer-graphics/khzvdpnsqfpg) |
| **EuroVis** | `eurovis/` | Eurographics | [EuroVis Template](https://www.overleaf.com/gallery/5985378946/eurovis-template) |

## Usage

### ACM Format (CHI, UIST, CSCW, DIS)

```latex
\documentclass[sigchi, review]{acmart}

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
Your introduction here.

\bibliographystyle{ACM-Reference-Format}
\bibliography{references}
\end{document}
```

Key files (download from official sources):
- `acmart.cls` - Main style file
- `ACM-Reference-Format.bst` - Bibliography style

### IEEE VIS/PacificVis Format

```latex
\documentclass[journal]{IEEEtran}

\begin{document}
\title{Your Paper Title}
\author{Author Name}
\IEEEauthorblockN{Author Name}
\IEEEauthorblockA{Your Institution\\
City, Country\\
Email: author@example.com}

\begin{abstract}
Your abstract here.
\end{abstract}

\maketitle

\section{Introduction}
Your introduction here.

\bibliographystyle{IEEEtran}
\bibliography{references}
\end{document}
```

Key files (download from official sources):
- `IEEEtran.cls` - Main style file
- `IEEEtran.bst` - Main style file

### EuroVis Format

```latex
\documentclass{egpubl}
\usepackage{eurovis2025}

\begin{document}
\title{Your Paper Title}
\author{Author Name}
\institute{Your Institution}
\email{author@example.com}

\begin{abstract}
Your abstract here.
\end{abstract}

\maketitle

\section{Introduction}
Your introduction here.

\bibliographystyle{eg-alpha}
\bibliography{references}
\end{document}
```

Key files (download from official sources):
- `egpubl.cls` - Eurographics base class
- `eurovis2025.sty` - EuroVis specific style
- `eg-alpha.bst` - Bibliography style

## Page Limits Summary

| Conference | Submission | Camera-Ready | Notes |
|------------|-----------|--------------|-------|
| CHI | 10 pages | 10 pages | +unlimited refs/appendix |
| UIST | 10 pages | 10 pages | +unlimited refs/appendix |
| IEEE VIS (TVCG) | 10 pages | 10 pages | +2 pages for refs |
| EuroVis (full) | 10 pages | varies | +unlimited refs/appendix |
| PacificVis | 8-10 pages | varies | +unlimited refs/appendix |
| CSCW | 10 pages | 10 pages | +unlimited refs/appendix |
| DIS | 10 pages | 10 pages | +unlimited refs/appendix |

## Common Issues

### Compilation Errors

1. **Missing packages**: Install full TeX distribution (TeX Live Full or MikTeX)
2. **Bibliography errors**: Use the provided `.bst` file with `\bibliographystyle{}`
3. **Font warnings**: Install `cm-super` or use `\usepackage{lmodern}`

### Anonymization

For submission, ensure:
- No author names in `\author{}`
- No acknowledgments section
- No grant numbers
- Use anonymous repositories
- Cite own work in third person

### Common LaTeX Packages

```latex
% Recommended packages (check compatibility with venue style)
\usepackage{amsmath,amsthm,amssymb}  % Math
\usepackage{graphicx}                 % Figures
\usepackage{booktabs}                 % Tables
\usepackage{hyperref}                 % Links
\usepackage{natbib}                   % Citations
% HCI/Vis specific:
\usepackage{tikz}                   % Diagrams
\usepackage{pgfplots}             % Plots
\usepackage{graphicx}                 % Figures
```

## Updating Templates

Templates are updated annually. Check official sources before each submission:

- ACM: https://www.acm.org/publications/authors/submission-templates
- IEEE: https://www.ieee.org/conferences/publishing/templates.html
- Eurographics: https://www.eg.org/wp/eurographics-publications/latex-templates/
