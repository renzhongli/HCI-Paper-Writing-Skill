# HCI/Visualization Paper Writing Philosophy & Best Practices

This reference compiles writing advice for HCI and visualization papers, combining general scientific writing principles with domain-specific guidance.

---

## Contents

- [The Narrative Principle](#the-narrative-principle)
- [Time Allocation](#time-allocation)
- [Abstract Writing Formula](#abstract-writing-formula)
- [Introduction Structure](#introduction-structure)
- [HCI/Vis Paper Structure](#hcivis-paper-structure)
- [Sentence-Level Clarity](#sentence-level-clarity)
- [Word Choice and Precision](#word-choice-and-precision)
- [Figure Design for HCI/Vis](#figure-design-for-hcivis)
- [Common Mistakes to Avoid](#common-mistakes-to-avoid)

---

## The Narrative Principle

### General Principle

"A paper is a short, rigorous, evidence-based technical story with a takeaway readers care about."

The narrative rests on three pillars that must be crystal clear by the end of your introduction:

**The "What"**: One to three specific novel claims fitting within a cohesive theme.

**The "Why"**: Rigorous empirical evidence that convincingly supports those claims—for HCI this often includes user studies, for visualization this includes evaluation studies and usage examples.

**The "So What"**: Why readers should care, connecting your contribution to problems the community recognizes as important.

### Practical Implication

If you cannot state your contribution in one sentence, you don't yet have a paper. Everything else—experiments, related work, discussion—exists only to support that core claim.

---

## Time Allocation

Spend approximately **the same amount of time** on each of:
1. The abstract
2. The introduction
3. The figures (critical for HCI/Vis!)
4. Everything else combined

This isn't hyperbole—most reviewers form preliminary judgments before reaching your methods section. Readers encounter your paper in a predictable pattern: **title → abstract → introduction → figures → maybe the rest.**

### Reviewer Reading Patterns

Studies of reviewer behavior show:
- Abstract is read 100% of the time
- Introduction is skimmed by 90%+ of reviewers
- Figures are examined before methods by most reviewers (especially in visualization)
- Full methods are read only if interest is established

**Implication**: Front-load your paper's value. Don't bury the contribution.

---

## Abstract Writing Formula

### 5-Sentence Formula (Adapted for HCI/Vis)

1. **Background**: This topic is timely and important
2. **Problems**: What specific problems exist in this context?
3. **Challenges**: What challenges do these problems reflect?
4. **Solution**: How did you address these challenges?
5. **Evidence**: What evidence supports your solution?

### What to Avoid

From Zachary Lipton: "If the first sentence can be pre-pended to any HCI/Vis paper, delete it."

**Delete these openings**:
- "Human-computer interaction is an important field..."
- "Data visualization has become increasingly..."
- "In recent years, interactive systems have..."

**Start with your specific contribution instead.**

---

## Introduction Structure

### Requirements

- **1-1.5 pages maximum** (in two-column format)
- **Methods should start by page 2-3**
- Must include **2-4 bullet contribution list** (max 1-2 lines each)

### Structure Template (HCI/Vis Focused)

```markdown
1. Opening Hook (2-3 sentences)
   - State the problem your paper addresses
   - Why it matters RIGHT NOW

2. Background/Challenge (1 paragraph)
   - What makes this problem hard?
   - What have others tried? Why is it insufficient?

3. Your Approach (1-2 paragraph)
   - What do you do differently?
   - Key insight that enables your contribution

4. Contribution Bullets (2-4 items)
   - Be specific and falsifiable
   - Each bullet: 1-2 lines maximum
```

### Contribution Bullets: Good vs Bad

**Good:**
- We present a novel visualization technique that reduces task completion time by 40%
- We conduct a user study with 24 participants demonstrating improved accuracy
- We introduce a framework that enables real-time interaction with large datasets

**Bad:**
- We study the problem of X (not a contribution)
- We provide extensive experiments (too vague)
- We make several contributions to the field (says nothing)

---

## HCI/Vis Paper Structure

HCI and visualization papers often follow specific structures depending on the contribution type:

### For System/Visualization Papers

1. **Abstract**
2. **Introduction**
3. **Related Work**
4. **Design Requirement**
5. **System**
6. **Evaluation** (user study, performance benchmarks, case studies)
7. **Discussion** (limitations, future work)
8. **Conclusion**
9. **References**


---

## Sentence-Level Clarity

### From Gopen & Swan: "The Science of Scientific Writing"

The seminal 1990 paper by George Gopen and Judith Swan establishes that **readers have structural expectations** about where information appears in prose. Violating these expectations forces readers to spend energy on structure rather than content.

> "If the reader is to grasp what the writer means, the writer must understand what the reader needs."

#### The 7 Principles of Reader Expectations

**Principle 1: Subject-Verb Proximity**

Keep grammatical subject and verb close together. Anything intervening reads as interruption of lesser importance.

**Weak**: "The system, which was designed for data exploration and includes several novel interaction techniques, achieves significant performance improvements"

**Strong**: "The system achieves significant performance improvements after being designed for data exploration with several novel interaction techniques"

**Principle 2: Stress Position (Save the Best for Last)**

Readers naturally emphasize the **last words of a sentence**. Place your most important information there.

**Weak**: "Accuracy improves by 35% when using our visualization"
**Strong**: "When using our visualization, accuracy improves by **35%**"

**Principle 3: Topic Position (First Things First)**

The beginning of a sentence establishes perspective. Put the "whose story" element first—readers expect the sentence to be about whoever shows up first.

**Weak**: "A novel interaction technique that supports direct manipulation is introduced"
**Strong**: "To address the manipulation problem, we introduce a novel interaction technique"

**Principle 4: Old Information Before New**

Put familiar information (old) in the topic position for backward linkage; put new information in the stress position for emphasis.

**Weak**: "Our technique was inspired by prior work. The limitations of existing methods motivate this approach."
**Strong**: "Existing methods have limitations. To address these, we present our technique inspired by prior work."

**Principle 5: One Unit, One Function**

Each unit of discourse (sentence, paragraph, section) should serve a single function. If you have two points, use two units.

**Principle 6: Articulate Action in the Verb**

Express the action of each sentence in its verb, not in nominalized nouns.

**Weak**: "We performed an analysis of the user study results" (nominalization)
**Strong**: "We analyzed the user study results" (action in verb)

**Principle 7: Context Before New Information**

Provide context before asking the reader to consider anything new. This applies at all levels—sentence, paragraph, section.

**Weak**: "Figure 3 shows that participants completed tasks 40% faster when using our system..."
**Strong**: "For task completion time, Figure 3 shows that participants were 40% faster when using our system..."

#### Summary Table

| Principle | Rule | Mnemonic |
|-----------|------|----------|
| Subject-Verb Proximity | Keep subject and verb close | "Don't interrupt yourself" |
| Stress Position | Emphasis at sentence end | "Save the best for last" |
| Topic Position | Context at sentence start | "First things first" |
| Old Before New | Familiar → unfamiliar | "Build on known ground" |
| One Unit, One Function | Each paragraph = one point | "One idea per container" |
| Action in Verb | Use verbs, not nominalizations | "Verbs do, nouns sit" |
| Context Before New | Explain before presenting | "Set the stage first" |

---

## Micro-Level Writing Tips

### Pronoun Management

**Minimize pronouns** ("this," "it," "these," "that"). When pronouns are necessary, use them as adjectives with a noun:

**Weak**: "This shows that the system is effective."
**Strong**: "This result shows that the system is effective."

**Weak**: "It improves user satisfaction."
**Strong**: "This technique improves user satisfaction."

### Verb Placement

**Position verbs early** in sentences for better parsing:

**Weak**: "The visualization, after being rendered and optimized, displays the data."
**Strong**: "The visualization displays the data after being rendered and optimized."

### Words to Eliminate

Delete these filler words in almost all cases:
- "actually"
- "a bit"
- "fortunately" / "unfortunately"
- "very" / "really"
- "quite"
- "basically"
- "essentially"
- Excessive connectives ("however," "moreover," "furthermore" when not needed)

### Sentence Construction Rules

1. **One idea per sentence** - If struggling to express an idea in one sentence, it needs two
2. **No repeated sounds** - Avoid similar-sounding words in the same sentence
3. **Every sentence adds information** - Delete sentences that merely restate
4. **Active voice always** - Specify the actor ("We find..." not "It is found...")
5. **Expand contractions** - "don't" → "do not" for formality

### Paragraph Architecture

- **First sentence**: State the point clearly
- **Middle sentences**: Support with evidence
- **Last sentence**: Reinforce or transition

Don't bury key information in the middle of paragraphs.

---

## Word Choice and Precision

### Eliminate hedging unless genuine uncertainty exists:
- Delete "may" and "can" unless necessary
- "provides *very* good results" drips with insecurity
- "provides good results" is confident

### Avoid vacuous intensifiers:
- Delete: very, extremely, highly, significantly (unless statistical)
- These words signal insecurity, not strength

### Precision over brevity: Replace vague terms with specific ones.

| Vague | Specific |
|-------|----------|
| performance | accuracy, task time, user satisfaction |
| improves | increases accuracy by X%, reduces time by Y |
| large | 1M data points, 1000 nodes |
| fast | 3x faster, 50ms latency |
| good results | 92% accuracy, 4.2/5 satisfaction |

### Consistent terminology: Referring to the same concept with different terms creates confusion.

**Choose one and stick with it**:
- "system" vs "tool" vs "application"
- "user" vs "participant"
- "visualization" vs "view" vs "display"

### Vocabulary Signaling

**Avoid words signaling incremental work**:
- Never: "combine," "modify," "expand," "extend"
- Instead: "develop," "propose," "introduce," "present"

**Why**: "We combine X and Y" sounds like you stapled two existing ideas together. "We develop a method that leverages X for Y" sounds like genuine contribution.

---

## Figure Design for HCI/Vis

### Critical for HCI/Visualization Papers

Figures are **especially important** in HCI and visualization papers. Many readers will look at your figures before reading the text.

### Design Principles

1. **Figure 1 is crucial**: Often the first thing readers examine after abstract
   - Should convey the core idea, system overview, or most compelling result
   - Consider a "teaser" figure showing your system in action

2. **Self-contained captions**: Reader should understand figure without main text
   - Explain what is shown
   - Explain what to look for
   - State key takeaways

3. **No title inside figure**: The caption serves this function

4. **Vector graphics**: PDF/EPS for all plots and diagrams
   - PNG (600 DPI) only for photographs or screenshots

5. **Accessibility Requirements**:
   - Use colorblind-safe palettes: Okabe-Ito or Paul Tol
   - Avoid red-green combinations
   - Verify figures work in grayscale
   - Use different line styles (solid, dashed, dotted) in addition to colors
   - 8% of men have color vision deficiency

### For Visualization Papers

- Show your visualization technique clearly
- Include before/after comparisons if applicable
- Demonstrate usage scenarios
- Show results from user studies or quantitative evaluations

### For HCI Systems Papers

- Show your system interface
- Include screenshots of key interactions
- Show study setup if applicable
- Present user study results clearly

---

## Common Mistakes to Avoid

### Structure Mistakes

| Mistake | Solution |
|---------|----------|
| Introduction too long (>1.5 pages) | Move background to Related Work |
| Methods buried (after page 3) | Front-load contribution, cut intro |
| Missing contribution bullets | Add 2-4 specific, falsifiable claims |
| Evaluation without clear claims | State what each experiment tests |

### Writing Mistakes

| Mistake | Solution |
|---------|----------|
| Generic abstract opening | Start with your specific contribution |
| Inconsistent terminology | Choose one term per concept |
| Passive voice overuse | Use active voice: "We show" not "It is shown" |
| Hedging everywhere | Be confident unless genuinely uncertain |

### Figure Mistakes

| Mistake | Solution |
|---------|----------|
| Raster graphics for plots | Use vector (PDF/EPS) |
| Red-green color scheme | Use colorblind-safe palette |
| Title inside figure | Put title in caption |
| Captions require main text | Make captions self-contained |

### Citation Mistakes

| Mistake | Solution |
|---------|----------|
| Paper-by-paper Related Work | Organize thematically |
| Missing relevant citations | Reviewers authored papers—cite generously |
| AI-generated citations | Always verify via APIs |
| Inconsistent citation format | Use BibLaTeX with consistent keys |

---

## Pre-Submission Checklist

Before submitting, verify:

**Narrative**:
- [ ] Can state contribution in one sentence
- [ ] Three pillars (What/Why/So What) clear in intro
- [ ] Every evaluation supports a specific claim

**Structure**:
- [ ] Abstract follows 5-sentence formula
- [ ] Introduction ≤1.5 pages
- [ ] Methods start by page 2-3
- [ ] 2-4 contribution bullets included
- [ ] Discussion/Limitations section present

**HCI/Vis Specific**:
- [ ] User study documented if applicable
- [ ] System/visualization clearly described
- [ ] Figures are high-quality and accessible
- [ ] Teaser/overview figure included (if appropriate)

**Writing**:
- [ ] Consistent terminology throughout
- [ ] No generic opening sentences
- [ ] Hedging removed unless necessary
- [ ] All figures have self-contained captions

**Technical**:
- [ ] All citations verified via API
- [ ] Ethical considerations addressed
- [ ] IRB obtained if needed
- [ ] Code/data availability stated
