# FFRN Conference 2025: Capturing the Data of Emotional Process

**A Day with Dr. Patrick Stinson**
*February 28, 2025 | Florida Family Research Network*

This repository contains all presentation materials for Dr. Stinson's full-day conference on family systems research, clinical psychology, and AI applications in behavioral health.

---

## Table of Contents

- [About This Repository](#about-this-repository)
- [Quick Links: Final Materials](#quick-links-final-materials)
- [Conference Schedule](#conference-schedule)
- [Repository Structure](#repository-structure)
- [Core Thesis](#core-thesis)
- [Reference Materials](#reference-materials)
  - [Dr. Stinson's Articles & Presentations](#dr-stinsons-articles--presentations)
  - [Historical Case Studies](#historical-case-studies)
- [The AI-Assisted Process](#the-ai-assisted-process)
- [Get Involved: Alaska Family Systems](#get-involved-alaska-family-systems)
  - [The Family Diagram App](#the-family-diagram-app)
  - [The App Seminar](#the-app-seminar)
  - [Research & Articles](#research--articles)
  - [Coming Soon: The Personal App](#coming-soon-the-personal-app)
  - [Open Source](#open-source)
- [About the Presenter](#about-the-presenter)
- [The Foundation: Stinson (2020) Dissertation](#the-foundation-stinson-2020-dissertation)
- [Contact](#contact)

---

## About This Repository

This repository serves two purposes:

1. **Conference Reference** - Index of all presentation materials, reference articles, and supporting research
2. **AI-Assisted Content Creation Demo** - A documented example of human-AI collaboration using Claude Code

All presentation content was developed through iterative collaboration between Dr. Stinson and Claude (Anthropic's AI assistant), with the human providing direction, corrections, and final judgment at each step. The AI assisted with research, drafting, organization, and source summarization.

---

## Quick Links: Final Materials

| Material | Description |
|----------|-------------|
| [Why Family? - Final Outline](1-WHY_FAMILY/9-Claude-Outline.md) | Current presentation outline (60 min) |
| [Event Schedule](EVENT_SCHEDULE.md) | Full day schedule |
| [Reference Articles](articles/) | All supporting research summaries |

---

## Conference Schedule

### Morning 1 - Orientation (8:30-10:00)
- Introduction by FFRN
- **Why Family? The State of Behavioral Health** - Dr. Stinson

### Morning 2 - AI & R&D (10:15-12:30)
- Intro to SARF
- Developing an AI Model for Clinical Evaluation

### Afternoon - Applications (1:15-4:00)
- The Family Diagram App
- Visualizing Emotional Process - Clinical Presentation (Dr. Havstad)
- Data, the Future, the Next Generation

---

## Repository Structure

```
.
├── README.md                    # This file
├── EVENT_SCHEDULE.md            # Full day schedule
├── CLAUDE.md                    # AI instruction file (meta-reference)
│
├── 1-WHY_FAMILY/                # "Why Family?" presentation
│   ├── 1-INITIAL_BRAINSTORM.md  # Starting point
│   ├── 2-Claude-Outline.md      # First AI draft
│   ├── ...                      # Iterations 3-8
│   └── 9-Claude-Outline.md      # CURRENT VERSION
│
├── 2-SARF_INTRO/                # "Intro to SARF" presentation
│
├── 3-CLINICAL_RESEARCH/         # "Clinical Research at the Cutting Edge"
│   ├── 0-INITIAL_BRAINSTORM.md  # Brainstorm and concepts
│   ├── 1-SLIDES-DRAFT.md        # Slide deck draft
│   └── DASHBOARD.md             # Development status
│
└── articles/                    # Reference materials
    ├── Stinson-*.md             # Dr. Stinson's published work
    └── [topic].md               # Historical case summaries
```
---

## Core Thesis

**"Everyone needs scientific thinking."**

The presentation argues that:

1. Clinical psychology lacks measurable, testable foundations
2. Untested practices spread through professions via social contagion
3. Historical catastrophes (lobotomy, recovered memory, etc.) demonstrate the danger
4. The family system is the smallest unit where emotional process becomes visible
5. Shifting the unit of analysis from individual to family enables scientific measurement

**Key concept:** Anxiety = perceived uncertainty + urgency. When anxious, people seek simple, untestable explanations that reduce uncertainty in the short term but obscure real problems long term.

---


## Reference Materials

### Dr. Stinson's Articles & Presentations

| File | Topic |
|------|-------|
| [Emotional Systems Research Methodology](articles/Stinson-Emotional-Systems-Research-Methodology.md) | Two-phase qualitative research methodology |
| [Induction and Family Diagram](articles/Stinson-Induction-and-Family-Diagram.md) | Induction vs deduction; the triangle as induction |
| [Daily Logging with Toward and Away](articles/Stinson-Daily-Logging-in-Family-Diagram-With-Toward-and-Away.md) | Atomic operations; daily logging for differentiation |
| [The Role of Modeling in Scientific Theory](articles/Stinson-The-Role-of-Modeling-in-Scientific-Theory.md) | Explicit predictive models; data models |
| [The Importance of the Timeline](articles/Stinson-The-Importance-of-the-Timeline-in-Family-Diagram.md) | Timeline construction; facts vs functional facts |
| [The Implicit Model](articles/Stinson-The-Implicit-Model.md) | Implicit vs explicit models; theory of change |

### Historical Case Studies

These summaries document professional catastrophes where well-intentioned interventions caused harm - supporting the presentation's thesis about the dangers of untested practices spreading through professions.

| File | Topic | Key Facts |
|------|-------|-----------|
| [Salem Witch Trials](articles/Salem-Witch-Trials.md) | 1692 | 25+ dead; spectral evidence; jurors apologized |
| [Lobotomy Epidemic](articles/Lobotomy-Epidemic.md) | 1940s-1960s | 50,000+ surgeries; 5% mortality; Nobel Prize |
| [Refrigerator Mother Theory](articles/Refrigerator-Mother-Theory.md) | 1950s-1970s | 20 years blaming mothers for autism |
| [Recovered Memory Therapy](articles/Recovered-Memory-Therapy.md) | 1980s-1990s | ~1 million patients; tens of thousands of families destroyed |
| [Satanic Panic](articles/Satanic-Panic-Daycare-Abuse.md) | 1980s-1990s | 12,000+ accusations; 0 substantiated by FBI |
| [MPD/DID Epidemic](articles/MPD-DID-Epidemic.md) | 1980s-1990s | 50,000 diagnoses vs ~200 prior; iatrogenic |
| [Cambridge-Somerville Youth Study](articles/Cambridge-Somerville-Youth-Study.md) | 1939-1979 | Treatment group did worse on all measures |

---

## The AI-Assisted Process

This repository demonstrates human-in-the-loop AI collaboration for content development.

### How It Worked

1. **Human provides direction** - Dr. Stinson specified thesis, audience, constraints, and corrections
2. **AI drafts and researches** - Claude generated outlines, summarized sources, organized material
3. **Human reviews and corrects** - Each iteration incorporated feedback and refinements
4. **AI revises** - Claude updated materials based on corrections
5. **Repeat** - 9 iterations for the main presentation

### Key Files Documenting the Process

| File | Purpose |
|------|---------|
| [CLAUDE.md](CLAUDE.md) | Instructions given to Claude for the project |
| [1-INITIAL_BRAINSTORM.md](1-WHY_FAMILY/1-INITIAL_BRAINSTORM.md) | Starting point before AI involvement |
| [2-Claude-Outline.md](1-WHY_FAMILY/2-Claude-Outline.md) | First AI-generated draft |
| [9-Claude-Outline.md](1-WHY_FAMILY/9-Claude-Outline.md) | Current version after 8 revision cycles |

### What the AI Did Well

- Organizing complex material into coherent structure
- Researching and summarizing historical sources
- Maintaining consistency across revisions
- Generating multiple options for human selection

### What Required Human Judgment

- Core thesis and argument direction
- Audience appropriateness
- Factual accuracy verification
- Tone and emphasis decisions
- Correcting AI misunderstandings (e.g., distinguishing "social contagion in professions" from "mental illness spreading")

---

## Get Involved: Alaska Family Systems

If the ideas in this presentation resonate with you, there are several ways to engage with this work.

### The Family Diagram App

A desktop application for clinicians and researchers to visualize and analyze family emotional process over time.

- **App Homepage:** [alaskafamilysystems.com/family-diagram](https://alaskafamilysystems.com/family-diagram/)
- **Features:** Timeline construction, relationship mapping, event tracking, multi-generational diagrams
- **Who it's for:** Clinicians, researchers, and anyone serious about understanding family systems

### The App Seminar

A monthly online seminar where practitioners explore the app, discuss cases, and develop the methodology together.

- **Learn more:** [alaskafamilysystems.com/family-diagram](https://alaskafamilysystems.com/family-diagram/) (seminar info)
- **Format:** Monthly Zoom sessions with Dr. Stinson and other Bowen theory practitioners
- **Focus:** Practical application, case consultation, methodology development

### Research & Articles

Dr. Stinson's published articles and presentations on family systems research methodology:

- **Main site:** [alaskafamilysystems.com](https://alaskafamilysystems.com)
- **Research page:** [alaskafamilysystems.com/research](https://alaskafamilysystems.com/research/)
- **Working paper:** [Anxiety as a Core Concept in Animal and Human Adaptation](https://docs.google.com/document/d/1uJo8IfAdBIc-PSD3d9N92nHgj_UPQEOU/edit?usp=sharing&ouid=107650946746379965892&rtpof=true&sd=true) - Theoretical framework for anxiety as perceived uncertainty + urgency
- **Topics covered:**
  - Anxiety as uncertainty + urgency (the "A" in SARF)
  - The role of modeling in scientific theory
  - Induction vs. deduction in family systems
  - The implicit model concept
  - Daily logging and the "toward/away" atomic operation
  - Timeline construction methodology

### Coming Soon: The Personal App

An AI-powered intake and reflection tool for individuals who want to understand their own patterns without requiring a clinician.

- Leverages the SARF data model
- AI-assisted pattern recognition
- Bridges personal reflection and clinical frameworks

### Open Source

The Family Diagram codebase is open source for those interested in the technical implementation:

- **GitHub:** [github.com/patrickkidd/familydiagram](https://github.com/patrickkidd/familydiagram)
- **AI Clinical Evaluation (btcopilot):** [github.com/patrickkidd/btcopilot](https://github.com/patrickkidd/btcopilot)


---

## About the Presenter

**Dr. Patrick Stinson, Psy.D.** brings a rare combination of deep technical expertise and clinical training to family systems research.

### Professional Background
- **25 years** as a software architect (professional audio, web, semiconductor validation, AI/ML)
- Currently **AI Engineer/Architect at Micron Technology**
- Founder of **Alaska Family Systems** (alaskafamilysystems.com)

### Clinical Training, Experience in Therapy
- **5-year** Masters + Doctoral program (California Institute of Integral Studies)
- **Pre- and Post-Doctoral internships** at The Bowen Center for the Study of the Family (Washington, DC)
- **5 years** of individual therapy (as patient)
- **2 years** in group therapy
- **2 years** of weekly Jungian analysis
- **3 years** in Bowen family coaching

### Current Work
- Maintaining the **Family Diagram "Pro" app** for clinicians and researchers
- Developing the **"Personal" AI intake app** for individuals
- Running the monthly **App Seminar** with Bowen theory practitioners
- Speaking engagements like this FFRN conference

---

## The Foundation: Stinson (2020) Dissertation

All of Dr. Stinson's work - SARF, the Family Diagram app, the Personal app, and AI R&D projects - originates from his 2020 doctoral dissertation on problems in psychological science.

**Key dissertation contributions:**
- Comprehensive literature review on challenges to psychology as a science
- Analysis of why behavioral health lacks measurable, testable foundations
- Proposal for shifting the unit of analysis from individual to family
- Introduction of the SARF data model as a minimal testable framework

**Dissertation excerpt included in this repo:**
- [Stinson (2020) - Chapter 2 - Challenges to Psychology as a Science](Stinson%20(2020)%20-%20Chapter%202%20-%20Challenges%20to%20Psychology%20as%20a%20Science%20-%20pages%2056%20-%2087.pdf) (pages 56-87)

The dissertation provides the intellectual foundation for why measurability matters, why the field is broken, and what a scientific approach to family emotional process might look like.

---

## Contact

**Dr. Patrick Stinson, Psy.D.**
Alaska Family Systems

- Website: [alaskafamilysystems.com](https://alaskafamilysystems.com)
- Family Diagram App: [alaskafamilysystems.com/family-diagram](https://alaskafamilysystems.com/family-diagram/)
- GitHub: [github.com/patrickkidd](https://github.com/patrickkidd)
- Email: patrickkidd@gmail.com

---

*This repository is an example of AI-assisted content creation. All final decisions and factual claims are the responsibility of the human author.*
