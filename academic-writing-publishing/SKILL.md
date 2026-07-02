# academic-writing-publishing v1.0.0

> Production-grade academic writing skill for Claude Code: craft → structure → polish → submit.
> Covers IMRaD architecture, abstract/title optimization, journal selection, cover letter drafting, and pre-submission compliance.

## Skill Overview

| Mode | Purpose | Output | Oversight |
|------|---------|--------|-----------|
| `full` | End-to-end paper writing coach | Structured draft guidance + rhetorical roadmap | High |
| `abstract-craft` | Abstract optimization | Polished 4-element abstract | Medium |
| `title-craft` | Title optimization | Title variants ranked by discoverability + impact | Low |
| `journal-fit` | Journal selection analysis | Ranked journal list + scope alignment report | Medium |
| `cover-letter` | Cover letter drafting | Venue-tailored cover letter | Low |
| `submission-checklist` | Pre-submission compliance audit | Pass/fail checklist per journal requirements | Low |
| `style-check` | Academic style audit | Formality, bias, precision, and hedging audit | Medium |

## Core Principles

### 1. IMRaD Architecture
All empirical papers follow Introduction → Methods → Results → Discussion/Conclusion.
Each section has a specific rhetorical job:
- **Introduction**: Establish territory → Create niche (gap) → Occupy niche (contribution)
- **Methods**: Reproducibility-first; justify every design choice
- **Results**: Data-driven, no interpretation; figures/tables lead
- **Discussion**: Interpret, compare with literature, acknowledge limitations, implications
- **Conclusion**: Thesis restatement + contribution + future directions

### 2. Claim-Evidence Discipline
Every claim requires a citation or direct evidence anchor. Evidence hierarchy:
- Meta-analyses / systematic reviews > RCTs > cohort studies > case reports > expert opinion
- Pre-print sources flagged with contamination advisory
- All claims scoped to evidence strength (avoid over-extrapolation)

### 3. Academic Register
- **Formal**: No contractions, slang, or colloquialisms
- **Precise**: Specific quantities over vague language
- **Impersonal**: Third person or first person where disciplinary norm permits
- **Hedged appropriately**: Hedging language proportional to evidence certainty
- **Unbiased**: Fair representation of competing findings and limitations

### 4. Citation Integrity
- Consistent citation style throughout (APA 7, MLA, Chicago, Vancouver, etc.)
- Cite primary sources; avoid over-reliance on secondary sources
- Verify all DOIs and publication details before submission
- Never fabricate or misrepresent source content

## Mode Specifications

### full - End-to-End Paper Writing Coach
**Triggers**: "help me write my paper", "guide me through writing a research paper", "full paper coaching"
**Output**: Structured guidance through all paper sections with rhetorical coaching
**Oversight**: High - user confirms RQ, contribution claim, and outline before drafting

**Workflow**:
1. **Intake**: Elicit research question, field, target journal (if known), available data/findings
2. **Contribution check**: Socratic framing - what is new/different/better about this work?
3. **Outline generation**: Section-by-section outline with word budget per section
4. **Section drafting**: Guided drafting with in-line rhetorical coaching (Intro to Methods to Results to Discussion to Abstract to Title)
5. **Style pass**: Formality, precision, hedging, and citation placement audit
6. **Pre-submission checklist**: Journal-specific compliance check

### abstract-craft - Abstract Optimization
**Triggers**: "write my abstract", "improve my abstract", "optimize abstract"
**Output**: Polished 4-5 element structured abstract
**Oversight**: Medium

**Elements** (each 1-4 sentences):
1. **Background/Context**: Why does this problem matter? What is already known?
2. **Objective/Aim**: What does this study specifically set out to do?
3. **Methods/Approach**: How was it done (study design, key techniques, sample)?
4. **Results/Findings**: What were the key quantitative or qualitative outcomes?
5. **Conclusions/Implications**: What do findings mean? What is the take-home message?

**Abstract rules**:
- Stay within word limit (typically 150-300 words)
- No citations unless mandatory by journal style
- No unexplained abbreviations
- Past tense for completed work; present tense for established facts
- Keywords aligned with database indexing terms

### title-craft - Title Optimization
**Triggers**: "write a title", "improve my title", "title suggestions"
**Output**: 3-5 title variants with rationale

**Title checklist**:
- 15 words or fewer for most journals
- Contains key terms for database searchability
- Avoids abbreviations unless universally known in field
- Front-loads the most important concept
- Avoids "A study of" or "An investigation of" openers

**Title types by discipline norm**:
- Descriptive: "Effects of X on Y in Z population"
- Question: "Does X affect Y in Z?" (common in social sciences)
- Declarative: "X reduces Y by 40%" (increasing in high-impact science journals)

### journal-fit - Journal Selection Analysis
**Triggers**: "which journal should I submit to", "journal selection", "where to submit"
**Output**: Ranked journal list with scope alignment analysis
**Oversight**: Medium

**Selection criteria**:
1. **Scope alignment**: Does the journal publish work in this exact area?
2. **Audience match**: Who reads it - who should read your work?
3. **Impact factor / CiteScore**: Realistic match to paper quality
4. **Open access requirements**: Funder mandates? APC costs?
5. **Turnaround time**: How urgent is publication?
6. **Acceptance rate**: Calibrate ambition to evidence quality
7. **Predatory screening**: DOAJ, Cabell's, COPE membership check

### cover-letter - Cover Letter Drafting
**Triggers**: "write cover letter", "draft cover letter", "submission letter"
**Output**: Venue-tailored cover letter (300-500 words)
**Oversight**: Low

**Structure**:
1. **Opening**: Paper title + journal name + explicit submission statement
2. **Significance statement**: Why this paper matters for this journal's readership
3. **Contribution statement**: What is new/different/better (gap filled)
4. **Methodological note**: Key design strength worth highlighting
5. **Conflicts/ethics**: Competing interests, IRB approval, data availability
6. **Suggested reviewers** (if required): 3-5 names with credentials
7. **Closing**: Author contact + corresponding author confirmation

### submission-checklist - Pre-Submission Compliance Audit
**Triggers**: "check submission requirements", "am I ready to submit", "submission checklist"
**Output**: Pass/fail compliance checklist
**Oversight**: Low

**Universal checks**:
- Word count within journal limit
- Abstract within word limit and correctly structured
- Keywords: correct number and format per journal instructions
- Author information complete (ORCID, affiliations, emails)
- Funding statement included
- Conflicts of interest declared
- Ethics statement / IRB approval number (if applicable)
- Data availability statement (mandated by growing number of journals)
- All figures: 300 DPI minimum, correct format, labeled with captions
- All tables: numbered, captioned, self-contained
- References: style-consistent, all DOIs active, no missing fields
- In-text citations match reference list (no orphans, no missing entries)
- File format correct (DOCX, LaTeX, PDF per journal instructions)
- Blinded for review if double-blind (no author names, affiliations, or identifying self-citations)
- Cover letter present and addressed to correct editor/journal
- Permissions: all third-party figures/tables cleared for reproduction

### style-check - Academic Style Audit
**Triggers**: "check my academic style", "style audit", "writing style review"
**Output**: Annotated style report with specific corrections
**Oversight**: Medium

**Style dimensions**:
1. **Formality**: Flag informal terms, contractions, colloquialisms
2. **Precision**: Flag vague quantifiers ("many", "few", "large") and suggest specific alternatives
3. **Hedging calibration**: Under-hedged claims ("proves") vs. over-hedging ("may possibly suggest")
4. **Bias and balance**: Loaded language, unrepresented counterevidence
5. **Sentence structure**: Passive/active voice balance; sentence length variety
6. **Paragraph structure**: One idea per paragraph; topic sentence + evidence + transition
7. **Jargon**: Undefined specialist terms; unnecessary complexity
8. **Tense consistency**: Past tense (methods/results), present tense (established knowledge)

## Section-Specific Rhetorical Guides

### Writing the Introduction (CARS Model)
Following Swales' Create A Research Space (CARS) model:

**Move 1 - Establish territory**: Show the topic is important and active
- "X has become a central challenge in..."
- "Recent work has demonstrated that..."

**Move 2 - Create a niche**: Identify a gap, problem, or contradiction
- "However, little is known about..."
- "Existing studies have not examined..."
- "Results across studies are contradictory..."

**Move 3 - Occupy the niche**: State your contribution clearly
- "This study addresses this gap by..."
- "We present the first systematic analysis of..."
- "The present paper argues that..."

### Writing the Methods
- Organize by: Participants/Sample → Design → Materials/Instruments → Procedure → Analysis
- Every step must be reproducible from description alone
- Justify non-standard choices explicitly
- Report all relevant ethical approvals and consent procedures
- Use past tense throughout

### Writing the Results
- Lead with the figure/table reference, then interpret in text
- Report effect sizes and confidence intervals alongside p-values
- Do not interpret - describe only; save interpretation for Discussion
- Present results in logical order mirroring Methods sequence
- Negative and null results are results - report them

### Writing the Discussion
**Structure**:
1. **Restate main finding** (conceptual summary without numbers)
2. **Interpret**: What does this mean? Why did this happen?
3. **Compare with literature**: Consistent with / contrary to prior work?
4. **Mechanistic explanation**: Why might the relationship exist?
5. **Limitations**: Internal validity, external validity, measurement limitations
6. **Implications**: Theoretical, practical, policy
7. **Future directions**: Specific, not generic

**Common Discussion errors to avoid**:
- Repeating Results without interpretation
- Ignoring contradictory findings
- Overstating generalizability beyond sample
- Omitting limitations

### Writing the Abstract (Order of Composition)
Write LAST - after the full paper is complete. Compress each major section:
- 1-2 sentences from Introduction (background + objective)
- 1-2 sentences from Methods (design + key analysis)
- 2-3 sentences from Results (key findings with numbers)
- 1-2 sentences from Discussion (conclusion + main implication)

## Common Publishing Pitfalls

| Pitfall | Description | Fix |
|---------|-------------|-----|
| Salami slicing | Splitting one study into too many papers | Report minimum publishable unit honestly |
| Selective reporting | Only reporting favorable findings | Pre-register and report all outcomes |
| Hallucinated citations | Non-existent or misrepresented references | Verify all citations before submission |
| Over-claiming | "Proves", "definitively shows" | Hedge appropriately per evidence strength |
| Missing limitations | Presenting only strengths | Devote dedicated paragraph to limitations |
| Inappropriate authorship | Gift or ghost authors | Follow ICMJE criteria for authorship |
| Journal scope mismatch | Submitting to wrong venue | Verify scope before submission |
| Inadequate blinding | Identifying information in blind review | Audit anonymization before uploading |

## Key Rules
1. All claims require evidence anchors (citation or direct data)
2. Evidence hierarchy respected throughout
3. Limitations disclosed honestly - do not minimize
4. AI usage disclosed per venue policy (ICMJE, NeurIPS, Nature, Science, ACL, etc.)
5. No fabricated citations or misrepresented sources
6. Pre-print sources flagged when used as primary evidence
7. Style consistency: one citation format, one spelling convention, consistent number formatting

## Integration with ARS Suite

This skill complements the existing academic-research-skills pipeline:

- **Upstream**: Use deep-research full or deep-research lit-review to generate the evidence base
- **Parallel**: Use academic-paper full mode for AI-assisted full paper drafting
- **Downstream**: Use academic-paper-reviewer full to simulate peer review on completed drafts
- **End-to-end**: academic-pipeline orchestrates the complete research to write to review to finalize workflow

**Trigger routing**:
- User wants to write from scratch with data: full mode
- User has a draft, needs style/register audit: style-check mode
- User needs abstract only: abstract-craft mode
- User unsure where to submit: journal-fit mode
- User ready to submit: submission-checklist mode

## Version Info
Version: 1.0.0
Last Updated: 2026-07-02
Sources: Swales CARS model (1990), PLOS Author Resources, Scribbr Research Paper Guide, APA Publication Manual 7th ed. (2020), ICMJE authorship criteria, ARS suite conventions (v3.14.0)
License: CC-BY-NC 4.0
