# HCI/Visualization Conference Paper Checklists

This reference documents the checklist requirements for major HCI and visualization conferences.

---

## Contents

- [CHI Paper Checklist](#chi-paper-checklist)
- [UIST Paper Checklist](#uist-paper-checklist)
- [IEEE VIS Requirements](#ieee-vis-requirements)
- [Universal Pre-Submission Checklist](#universal-pre-submission-checklist)

---

## CHI Paper Checklist

### Key Requirements

CHI follows ACM SIGCHI requirements. All submissions must adhere to the SIGCHI format and guidelines.

### CHI 10-Point Checklist

#### 1. Contribution Clarity
Authors must clearly articulate the paper's contributions, with explicitly stated contributions, assumptions, and limitations.

**What to check:**
- [ ] Abstract clearly states contributions
- [ ] Introduction doesn't overclaim
- [ ] Contributions are specific and meaningful

#### 2. User Studies (if applicable)
Papers involving human subjects must include detailed study design, participant recruitment, ethical considerations, and analysis.

**What to include:**
- [ ] Detailed study design
- [ ] Participant demographics
- [ ] Ethical considerations (IRB, consent)
- [ ] Analysis methods

#### 3. Visualization/System Description
For visualization or systems papers, provide clear descriptions of the system, design rationale, and implementation details.

**What to document:**
- [ ] System architecture
- [ ] Design decisions and rationale
- [ ] Implementation details
- [ ] Technical specifications

#### 4. Reproducibility
Authors should describe steps ensuring results verification through code release, detailed instructions, or demo videos.

**What to provide:**
- [ ] Clear reproducibility statement
- [ ] Code availability information
- [ ] Demo video if applicable
- [ ] Supplementary materials

#### 5. Ethical Considerations
All papers must address ethical considerations, especially for human subjects research, data collection, and potential societal impacts.

**What to address:**
- [ ] IRB approval if applicable
- [ ] Informed consent process
- [ ] Privacy considerations
- [ ] Potential negative impacts
- [ ] Mitigation strategies

#### 6. Related Work
Thoroughly discuss related work, positioning the paper within the broader HCI/Vis literature.

**What to check:**
- [ ] Relevant work cited
- [ ] Clear positioning relative to prior work
- [ ] No unfair criticism

#### 7. Figures & Visuals
All figures should be high-quality, readable, and properly captioned.

**What to include:**
- [ ] High-resolution figures
- [ ] Clear captions
- [ ] Colorblind-safe palettes
- [ ] Accessibility considerations

#### 8. Discussion & Limitations
Include a dedicated "Discussion" or "Limitations" section addressing scope constraints and future work.

**What to include:**
- [ ] Dedicated Discussion/Limitations section
- [ ] Honest assessment of scope
- [ ] Conditions where method may fail
- [ ] Future work directions

#### 9. Artifact Submission
CHI encourages artifact submission and evaluation.

**What to consider:**
- [ ] Artifact submission option
- [ ] Documentation for artifacts
- [ ] License information

#### 10. Formatting Compliance
Ensure the paper adheres to ACM SIGCHI format requirements.

**What to verify:**
- [ ] Correct ACM format
- [ ] Page limits respected
- [ ] References properly formatted
- [ ] No author info in submission

---

## UIST Paper Checklist

### Key Requirements

UIST focuses on technical contributions in user interface software and technology.

### UIST Specific Requirements

#### Technical Depth
- [ ] Clear technical contribution
- [ ] Technical details sufficient for reproduction
- [ ] Evaluation of technical contributions

#### Demo Option
- [ ] Consider demo submission
- [ ] Video documentation if demo

---

## IEEE VIS Requirements

### TVCG Journal Format

IEEE VIS papers are published in IEEE Transactions on Visualization and Computer Graphics (TVCG).

### VIS Specific Requirements

#### Two-Stage Review
- [ ] First stage: 4-page short paper
- [ ] Second stage: full revision

#### Reproducibility
- [ ] Code/data availability
- [ ] Detailed implementation details

---

## Universal Pre-Submission Checklist

### Before Every Submission

#### Paper Content

- [ ] Abstract ≤ word limit (usually 150-250 words
- [ ] Main content within page limit
- [ ] References complete and verified
- [ ] Discussion/Limitations section included
- [ ] All figures/tables have captions
- [ ] Captions are self-contained

#### Formatting

- [ ] Correct template used (venue + year specific)
- [ ] Margins not modified
- [ ] Font sizes not modified
- [ ] Double-blind requirements met
- [ ] Page numbers (for review) or none (camera-ready)

#### Technical

- [ ] All claims supported by evidence
- [ ] User studies documented (if applicable)
- [ ] System/visualization described clearly
- [ ] Ethical considerations addressed

#### Reproducibility

- [ ] Code will be available (or justification)
- [ ] Data will be available (or justification)
- [ ] Environment documented
- [ ] Instructions to reproduce provided

#### Ethics

- [ ] Broader impacts considered
- [ ] Limitations honestly stated
- [ ] Licenses respected
- [ ] IRB obtained if needed

#### Final Checks

- [ ] PDF compiles without errors
- [ ] All figures render correctly
- [ ] All citations resolve
- [ ] Supplementary material organized
- [ ] Conference checklist completed

---

## Quick Reference: Page Limits

| Conference | Main Content | References | Appendix |
|------------|-------------|------------|----------|
| CHI | 10 pages | Unlimited | Unlimited |
| UIST | 10 pages | Unlimited | Unlimited |
| IEEE VIS (TVCG) | 10 pages | 2 pages | Unlimited |
| EuroVis (full) | 10 pages | Unlimited | Unlimited |
| PacificVis | 8-10 pages | Unlimited | Unlimited |

---

## Template Locations

All conference template instructions are in the `templates/` directory:

```
templates/
├── acm-format/     # CHI, UIST, CSCW, DIS (ACM format)
├── ieee-vis/    # IEEE VIS, PacificVis (IEEE format)
└── eurovis/     # EuroVis (Eurographics format)
```
