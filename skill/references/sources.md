# Source Bibliography for HCI/Visualization Paper Writing

This document lists all authoritative sources used to build this skill, organized by topic.

---

## Contents

- [Writing Philosophy & Guides](#writing-philosophy--guides)
- [HCI/Visualization Writing Guides](#hcivisualization-writing-guides)
- [Foundational Scientific Writing](#foundational-scientific-writing)
- [Official Conference Guidelines](#official-conference-guidelines)
- [Citation APIs & Tools](#citation-apis--tools)
- [Visualization & Formatting](#visualization--formatting)
- [Quick Reference by Topic](#quick-reference-by-topic)

---

## Writing Philosophy & Guides

### Primary Sources (Must-Read)

| Source | Author | URL | Key Contribution |
|--------|--------|-----|------------------|
| **Highly Opinionated Advice on How to Write ML Papers** | Neel Nanda | [Alignment Forum](https://www.alignmentforum.org/posts/eJGptPbbFPZGLpjsp/highly-opinionated-advice-on-how-to-write-ml-papers) | Narrative framework, "What/Why/So What", time allocation |
| **How to Write ML Papers** | Sebastian Farquhar (DeepMind) | [Blog](https://sebastianfarquhar.com/on-research/2024/11/04/how_to_write_ml_papers/) | 5-sentence abstract formula, structure templates |
| **A Survival Guide to a PhD** | Andrej Karpathy | [Blog](http://karpathy.github.io/2016/09/07/phd/) | Paper structure recipe, contribution framing |
| **Heuristics for Scientific Writing** | Zachary Lipton (CMU) | [Blog](https://www.approximatelycorrect.com/2018/01/29/heuristics-technical-scientific-writing-machine-learning-perspective/) | Word choice, section balance, intensifier warnings |
| **Advice for Authors** | Jacob Steinhardt (UC Berkeley) | [Blog](https://jsteinhardt.stat.berkeley.edu/blog/advice-for-authors) | Precision over brevity, consistent terminology |
| **Easy Paper Writing Tips** | Ethan Perez (Anthropic) | [Blog](https://ethanperez.net/easy-paper-writing-tips/) | Micro-level tips, apostrophe unfolding, clarity tricks |

---

## HCI/Visualization Writing Guides

### CHI Writing Resources

| Source | URL | Key Contribution |
|--------|-----|------------------|
| **CHI Paper Writing Guide** | [SIGCHI](https://sigchi.org/) | Official CHI submission guidelines and best practices |
| **How to Write a CHI Paper** | [Various Guides](https://medium.com/@howtowriteachi) | Practical advice from CHI authors and reviewers |
| **CHI Reviewer Guidelines** | [CHI Conference](https://chi2025.acm.org/) | Understanding the four review dimensions |

### Visualization Writing Resources

| Source | URL | Key Contribution |
|--------|-----|------------------|
| **IEEE VIS Author Guidelines** | [IEEE VIS](https://ieeevis.org/) | TVCG submission requirements and formatting |
| **How to Write a Visualization Paper** | [VisGuides](https://www.visguides.org/) | Advice for visualization research papers |

### HCI Research Methods

| Source | URL | Key Contribution |
|--------|-----|------------------|
| **User Study Design for HCI** | [HCI Methods](https://www.hcimethods.org/) | Designing and reporting user studies |
| **Statistics for HCI** | [HCI Stats](https://www.hcistats.org/) | Statistical methods for HCI research |

---

## Foundational Scientific Writing

| Source | Author | URL | Key Contribution |
|--------|--------|-----|------------------|
| **The Science of Scientific Writing** | Gopen & Swan | [PDF](https://cseweb.ucsd.edu/~swanson/papers/science-of-writing.pdf) | Topic/stress positions, old-before-new, 7 principles |
| **Summary of Science of Scientific Writing** | Lawrence Crowl | [Summary](https://www.crowl.org/Lawrence/writing/GopenSwan90.html) | Condensed version of Gopen & Swan |

### Additional Resources

| Source | URL | Key Contribution |
|--------|-----|------------------|
| Bill Freeman's Writing Slides | [MIT](https://billf.mit.edu/sites/default/files/documents/cvprPapers.pdf) | Visual guide to paper structure |

---

## Official Conference Guidelines

### CHI

| Document | URL | Purpose |
|----------|-----|---------|
| CHI Author Guidelines | [CHI 2025](https://chi2025.acm.org/) | Submission requirements, four review dimensions |
| ACM LaTeX Templates | [ACM](https://www.acm.org/publications/authors/submission-templates) | LaTeX templates for ACM conferences |

### UIST

| Document | URL | Purpose |
|----------|-----|---------|
| UIST Author Guidelines | [UIST](https://uist.acm.org/) | Submission requirements and formatting |
| ACM LaTeX Templates | [ACM](https://www.acm.org/publications/authors/submission-templates) | Same ACM format as CHI |

### IEEE VIS

| Document | URL | Purpose |
|----------|-----|---------|
| IEEE VIS Author Guidelines | [IEEE VIS](https://ieeevis.org/) | TVCG submission requirements |
| IEEE LaTeX Templates | [IEEE](https://www.ieee.org/conferences/publishing/templates.html) | LaTeX templates for IEEE conferences |

### EuroVis

| Document | URL | Purpose |
|----------|-----|---------|
| EuroVis Author Guidelines | [EuroVis](https://www.eurovis.org/) | Submission requirements, Eurographics format |
| Eurographics LaTeX Templates | [Eurographics](https://www.eg.org/wp/eurographics-publications/latex-templates/) | LaTeX templates for Eurographics |

---

## Citation APIs & Tools

### APIs

| API | Documentation | Best For |
|-----|---------------|----------|
| **Semantic Scholar** | [Docs](https://api.semanticscholar.org/api-docs/) | HCI/Vis papers, citation graphs |
| **CrossRef** | [Docs](https://www.crossref.org/documentation/retrieve-metadata/rest-api/) | DOI lookup, BibTeX retrieval |
| **arXiv** | [Docs](https://info.arxiv.org/help/api/basics.html) | Preprints, PDF access |
| **OpenAlex** | [Docs](https://docs.openalex.org/) | Open alternative, bulk access |

### Python Libraries

| Library | Install | Purpose |
|---------|---------|---------|
| `semanticscholar` | `pip install semanticscholar` | Semantic Scholar wrapper |
| `arxiv` | `pip install arxiv` | arXiv search and download |
| `habanero` | `pip install habanero` | CrossRef client |

### Citation Verification

| Tool | URL | Purpose |
|------|-----|---------|
| Citely | [citely.ai](https://citely.ai/citation-checker) | Batch verification |
| ReciteWorks | [reciteworks.com](https://reciteworks.com/) | In-text citation checking |

---

## Visualization & Formatting

### Figure Creation

| Tool | URL | Purpose |
|------|-----|---------|
| **SciencePlots** | [GitHub](https://github.com/garrettj403/SciencePlots) | Publication-ready matplotlib styles |
| **Okabe-Ito Palette** | [Reference](https://jfly.uni-koeln.de/color/) | Colorblind-safe colors |
| **Seaborn** | [Seaborn](https://seaborn.pydata.org/) | Statistical data visualization |
| **Matplotlib** | [Matplotlib](https://matplotlib.org/) | Comprehensive plotting library |
| **D3.js** | [D3.js](https://d3js.org/) | Interactive visualizations for the web |

### HCI/Vis Specific Tools

| Tool | URL | Purpose |
|------|-----|---------|
| **TikZ/PGFPlots** | [PGFPlots](https://pgfplots.sourceforge.net/) | LaTeX-native diagrams and plots |
| **Inkscape** | [Inkscape](https://inkscape.org/) | Vector graphics editing |
| **Adobe Illustrator** | [Illustrator](https://www.adobe.com/products/illustrator.html) | Professional figure preparation |

### LaTeX Resources

| Resource | URL | Purpose |
|----------|-----|---------|
| **Overleaf Templates** | [Overleaf](https://www.overleaf.com/latex/templates) | Online LaTeX editor with HCI/Vis templates |
| **BibLaTeX Guide** | [CTAN](https://ctan.org/pkg/biblatex) | Modern citation management |
| **booktabs** | [CTAN](https://ctan.org/pkg/booktabs) | Professional table formatting |

---

## Quick Reference by Topic

### For Narrative & Structure
→ Start with: Neel Nanda, Sebastian Farquhar, Andrej Karpathy

### For Sentence-Level Clarity
→ Start with: Gopen & Swan, Ethan Perez, Zachary Lipton

### For Word Choice & Style
→ Start with: Zachary Lipton, Jacob Steinhardt

### For HCI/Vis Specific Writing
→ Start with: CHI Author Guidelines, VisGuides, HCI Methods

### For User Study Writing
→ Start with: HCI Methods, HCI Stats, CHI Reviewer Guidelines

### For Conference-Specific Requirements
→ Start with: Official venue guidelines (CHI, UIST, IEEE VIS)

### For Citation Management
→ Start with: Semantic Scholar API, CrossRef, citation-workflow.md

### For Reviewer Expectations
→ Start with: Venue reviewer guidelines, reviewer-guidelines.md
