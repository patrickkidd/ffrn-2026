# Presentation 3: Clinical Research at the Cutting Edge

## Brainstorm & Concepts

**FFRN Conference | Feb 28, 2025**
**Duration:** 45 minutes (11:15-12:00)
**Follows:** Intro to SARF (establishes the data model)

---

## Core Frame

**How do we actually test whether any of this works?**

This presentation is a glimpse into how to research this stuff—and how we *are* researching it. Not a detailed technical walkthrough; low-resolution with room for questions and discussion.

---

## The Scaling Problem: Big Data vs. Small Data

### Big Data
- Millions of records, simple variables
- Machine-readable (insurance claims, lab results, surveys)
- Easy to automate

### Small Data (Our Problem)
- Rich qualitative information
- Requires interpretation and intelligent inference
- Clinical interviews, family history, emotional process
- You can't just run it through a spreadsheet

### Why This Research Never Happened

To test SARF, someone has to code cases:
- Read/listen to clinical interviews
- Identify shifts in S, A, R, F
- Record them on a timeline

**Previously:** Humans doing this tediously, by hand.
- Doesn't scale
- Doesn't get done unless it's your day job
- Can't get funding or momentum for a hypothetical model with simple but deep concepts

**What changed:** Machine automation now makes intelligent inference possible at scale.

---

## Domain-Expert Ground Truth

**Ground truth = what the domain experts agreed on.**

This is the formal concept that dispels "machines taking over":

1. Train human domain experts on SARF
2. Have them code cases independently (blind)
3. Measure agreement (IRR)
4. Cases where they agree = ground truth

**The machines don't decide what's correct. Humans do.**

- Software learns to replicate human expert judgment
- Every output can be reviewed and corrected
- Domain experts remain the authority

*Ground truth is human truth.*

---

## Synthetic Data: Discoveries

### Modeling Clinical Discussion

To train humans and test software, we needed data. Solution: generate synthetic clinical discussions.

- Realistic scenarios, SARF-codeable content
- Controlled environment for training and testing
- Test automated coding against human ground truth

### Discovery #1: Mutual Discovery

**You can't survey for this data like a knee problem.**

The coach/therapist must be in a process of *mutual discovery* with the client:
- Not extracting answers
- Exploring together
- The relationship affects what emerges

*If you just interrogate, you don't get the data you need for the model.*

### Discovery #2: Synthetic Data Trains Faster

The working group reported learning SARF coding much faster on synthetic data than real cases.

- Cleaner examples
- Known ground truth
- Faster iteration

*Real audio recordings are the ultimate goal. Synthetic data accelerates getting there.*

---

## Original Core Question (Still Relevant)

**How do you know if a clinical evaluation is accurate?**

Without an answer, you can't:
- Train people consistently
- Scale clinical knowledge
- Test competency
- Aggregate data for research
- Build tools that assist clinicians

---

## The R&D Pipeline (What Real Research Looks Like)

### Stage 1: Inter-Rater Reliability (IRR) Study

**The fundamental question:** Can trained humans agree on SARF coding?

- Web-based app for managing case coding
- Blind coding by domain experts
- Multiple coders per case
- Statistical measurement of agreement

**Why this matters:**
- If experts can't agree, the concepts aren't clear enough
- Forces operational definitions (no hand-waving)
- Creates gold-standard training data
- Reveals where the framework needs refinement

**What it produces:**
- IRR statistics (publishable)
- Curated dataset of coded cases
- Refined operational definitions
- Evidence that SARF is (or isn't) measurable

### Stage 2: AI Model Training

**Only possible IF Stage 1 succeeds.**

- Train on IRR-validated human judgments
- Model learns to replicate what humans agreed on
- Can only be as good as human agreement (ceiling effect)

**Key insight:** The AI doesn't replace clinical judgment—it replicates the *consensus* of trained humans.

### Stage 3: Application Layer

**Personal App (in development)**
- AI-assisted intake/reflection tool
- Generates timeline + family diagram via conversation
- For individuals (no clinician required)
- Outputs case file compatible with Pro app
- Bridge: self-help → clinical work

**Pro App (released)**
- SARF variables built into data model
- Timeline + diagram visualization
- For clinicians and researchers
- Can import Personal app cases as intake

**Training App (R&D)**
- Manages IRR study
- Could become training/certification tool
- Practice coding → feedback → competency

---

## The Personal App: Clustering Concept (Brief)

**Not a deep dive—just illustrate the concept with a visual.**

### Clustering as Clinical/Theoretical Idea

Events from a person's life naturally group into meaningful clusters:
- "Work responsibility accumulation"
- "Family conflict around holidays"
- "Health symptoms following relationship stress"

**The value:** Simply having everything listed and grouped is powerful—patterns become visible that were invisible when living through them.

### Anecdote: The Responsibility Pattern

Two 45-minute interviews with an expert. Person sees for the first time:
- Pattern of constantly picking up responsibility, no filter
- A variable going up and up—no downs
- Had never seen it; on timeline, undeniable

**Point:** You don't need sophisticated predictions. Just *seeing* the data organized is often the breakthrough.

### Visual

Screenshot showing clusters—communicates the concept quickly. Don't dwell on app features.

---

## Downstream Effects (The "So What")

### 1. Something Concrete to Sell Training Programs

Current state: Training programs have no standardized outcome measure.
- "Graduate from our program" = what exactly?
- No way to compare programs
- No way to measure trainee progress objectively

With validated SARF:
- Standardized competency metric
- Comparison across programs
- Evidence of training effectiveness

### 2. Standardized Clinical Evaluation

Current state: Every clinician does evaluation differently.
- Idiosyncratic intake processes
- No common language across practitioners
- Can't aggregate data

With SARF:
- Common framework (minimum, not comprehensive)
- Comparable evaluations
- Foundation for research collaboration

### 3. Certification / Competency Testing (THE HOOK)

**This is potentially the most compelling downstream effect for this audience.**

**SARF "Test" concept:**
- Present standardized cases
- Trainee codes them
- Compare to gold-standard IRR coding
- Objective competency measure

**Why this matters:**

This doesn't exist *anywhere* in family therapy training today. Not in the Bowen network. Not outside it. Training programs have:
- No standardized outcome measure
- No way to compare trainees across programs
- No way to know if training actually worked
- No way to certify competency objectively

The field operates on: "You graduated from our program, therefore you're trained."

**This is more concrete than anything this professional network has produced in decades.**

Even at early stage, the *framework* for certification is clearer than anything else on offer. The existence of:
1. A minimal data model (SARF)
2. A method to test agreement (IRR)
3. A database of gold-standard cases
4. A mechanism to compare trainee coding to gold standard

...is already more infrastructure than family therapy training has ever had.

**Framing for audience:** "Imagine knowing whether your training actually produced competent evaluators. Imagine trainees being able to demonstrate competency objectively. This is what becomes possible."

### 4. Aggregate Research Data

If many clinicians use same framework:
- Anonymized aggregate datasets possible
- Statistical patterns across cases
- Foundation for epidemiological research

### 5. AI as Intake Assistant

Personal app as pre-clinical tool:
- Client arrives with structured history already captured
- Clinician reviews, refines, proceeds
- Reduces intake time, increases consistency

---

## What Makes This "Real" R&D

**Contrast with typical Bowen theory "research":**

| Typical | This R&D |
|---------|----------|
| Single case study | Multiple coders, multiple cases |
| One person's interpretation | Blind, independent coding |
| No measurement | Statistical IRR metrics |
| Unfalsifiable | Falsifiable (IRR fails or succeeds) |
| Illustrative | Predictive (eventually) |
| Jargon-dependent | Operationally defined |

**Key principles:**
1. Starts with measurement (can we agree?)
2. Iterative (pilot → validation → scale)
3. Produces artifacts (apps, data, models)
4. Forces conceptual clarity
5. Invites critique (publishable, replicable)

---

## Technology/AI: Keep It in the Background

**The problem:** Audience is behind on AI adoption, afraid of it, and unable to stop focusing on it once mentioned. Deepest fear: being made irrelevant.

**The frame:** AI/technology is a *means to an end*, not the point. The story is about how to research clinical evaluation. Technology is just how you scale what humans validate.

### Audience Fears to Address

1. **AI taking over** → Emphasize human-in-the-loop (always reviewable, correctable)
2. **Things happening unattended** → Clinician remains decision-maker
3. **Being made irrelevant** → "Spell-check, not author" — technology assists, doesn't replace

### Strategic Framing

**Don't lead with AI. Don't dwell on AI mechanics.**

Lead with:
1. The problem (can't measure clinical evaluation)
2. The research method (IRR—can humans agree?)
3. Then, briefly: technology scales what humans validated

**Language choices:**
- Prefer "technology" or "software" over "AI" where possible
- "Assists" not "does"
- "Human-in-the-loop" — say it explicitly
- "The clinician reviews and decides"

### Key Lines

- "The human never leaves the loop."
- "Technology replicates what humans validated."
- "Think: spell-check, not author."
- "Every output can be reviewed and corrected."
- "The clinician remains the decision-maker."

### What NOT to Do

- Don't explain AI mechanics in detail
- Don't make AI sound impressive or magical
- Don't let AI become the topic of discussion
- Don't promise AI capabilities beyond current reality

The goal: their minds stay on the clinical arguments. Technology is one tool of many, in the background.

---

## Key Tensions / Honest Limitations

### AI Doesn't Replace Clinical Judgment
- AI replicates human consensus, not divine truth
- Garbage in → garbage out
- Still requires trained humans to validate

### IRR Might Fail
- If humans can't agree, we learn something
- Forces revision of the framework
- Null result is still a result

### Framework is Minimal by Design
- SARF doesn't claim to capture everything
- It's a floor, not a ceiling
- Complexity added as evidence permits

### Current State is Early
- IRR study in pilot phase
- Personal app in development
- No published results yet
- Showing the *process*, not claiming success

---

## Audience Considerations

**This is non-technical audience:**
- Don't go deep on AI/ML mechanics
- Focus on the *why* and *so what*
- Concrete examples > abstract concepts
- Avoid STEM jargon as much as Bowen jargon

**They might wonder:**
- "Is AI going to replace therapists?" → No, it replicates trained human judgment
- "How is this different from what we do?" → Measurement, standardization, falsifiability
- "When can I use this?" → Personal app coming, Pro app available now

---

## Possible Structure (Revised)

1. **The Problem** (5 min)
   - How do you know if clinical evaluation is accurate?
   - Training without measurement
   - Status quo: idiosyncratic, non-comparable, no certification

2. **The Human Foundation: IRR** (10 min)
   - Can trained humans agree on SARF coding?
   - This is the foundation—everything depends on it
   - What it produces: gold-standard cases, refined definitions
   - **Vignette:** Walk through coding example

3. **AI Demystified** (5 min)
   - Brief: pattern matching, learns from examples, ceiling effect
   - Pop the sci-fi balloon early
   - Frame: AI is the scaling mechanism, not the point

4. **Clustering & the Personal App** (5 min)
   - Clustering as clinical concept (events grouped by theme/pattern)
   - Screenshot visual
   - **Anecdote:** Responsibility pattern—A up and up, no downs, visible after 2 interviews
   - Key insight: just seeing data organized is often the breakthrough

5. **The Vision: Certification** (10 min)
   - What becomes possible
   - Objective competency testing
   - More concrete than anything the field has produced
   - Aggregate research data
   - Pro App + Training infrastructure

6. **Honest State & Limitations** (5 min)
   - Early stage—showing the process
   - IRR might fail (that's still a result)
   - AI doesn't replace judgment, it assists

**Note:** No live demos needed. Screenshots, diagrams, vignettes, anecdotes.

---

## Open Questions

- ~~How much to demo?~~ → No live demos needed. Screenshots/diagrams sufficient.
- ~~Should I show actual IRR data?~~ → No data yet (first IRR meeting next week). Show screenshots and method instead.
- How to make coding process concrete without boring them?
- ~~Balance between inspiring and honest about early stage?~~ → Not worried about underwhelming. Honest framing is fine.
- Tie back to Presentations 1-2 how explicitly?
- How much AI demystification is enough? Risk of spending too long on it.

---

## What to Show: Infrastructure, Not Results

**First IRR meeting is next week.** No data to present. This is fine—the story is the *infrastructure and method*, not results.

**The frame:** "Here's what we're building. Here's how rigorous it is. Here's why it matters."

### Screenshots / Visuals to Consider

Show sophistication without overwhelming:

1. **IRR App Interface**
   - Case management view (anonymized)
   - Blind coding workflow
   - How coders don't see each other's work

2. **The Coding Process**
   - A timeline with events
   - SARF variable options
   - What a coded case looks like

3. **Agreement Measurement**
   - Conceptual: how we'll calculate IRR
   - What "agreement" means statistically (brief)

4. **The Pipeline Diagram**
   - Simple flowchart: Cases → Blind Coding → IRR Stats → Gold Standard → AI Training
   - Shows the rigor without requiring tech knowledge

### What This Communicates

- "This isn't someone's weekend project"
- "Real infrastructure exists"
- "The method is defensible"
- "We're doing this properly"

The sophistication of the infrastructure *is* the credibility. For an audience used to case studies and theoretical speculation, seeing actual research tooling is novel.

---

## Concrete Vignettes: Making Coding Tangible

**Source options:** Personal journal entries or anonymized case examples.

### What a Good Vignette Shows

A vignette should be:
- **Brief** — 3-5 timeline events max
- **Relatable** — everyday situations the audience recognizes
- **Codeable** — clear enough that SARF variables apply

### Example Structure

```
TIMELINE:
- [Date] Event 1: Description
- [Date] Event 2: Description
- [Date] Event 3: Description

SARF CODING:
- S (Symptom): [what changed, up/down/same]
- A (Anxiety): [what changed, up/down/same]
- R (Relationship): [what shift—conflict, distance, reciprocal, etc.]
- F (Functioning): [what changed, up/down/same]
```

### What This Demonstrates

1. **The coding is doable.** It's not magic or requiring years of training to attempt.
2. **The variables are concrete.** Not vague theoretical abstractions.
3. **Disagreement is possible.** "You might code this as conflict, I might code it as distance—that's what IRR measures."
4. **The timeline matters.** Sequence reveals the R → A → S pipeline.

### Vignette Ideas

**From journal (personal, relatable):**
- Work stress → sleep problems → snapping at spouse
- Family visit → old patterns resurface → symptom flare
- Conflict with colleague → rumination → physical tension

**From case (clinical, demonstrates method):**
- Client presents with anxiety
- Timeline reveals relationship shift (cutoff, conflict, etc.)
- Coding shows R → A → S correlation

### How to Present

Option A: **Walk through one vignette live**
- Show timeline on screen
- Talk through coding choices
- Note where disagreement might occur

Option B: **Show two coders' different codes**
- Same vignette, two interpretations
- "This is what IRR measures—can we agree?"
- Makes the methodology concrete

Option C: **Before/after**
- Raw timeline (just events)
- Coded timeline (with SARF)
- Shows the transformation

### Keep It Light

The vignette isn't the point—it's a vehicle to show:
- What coding looks like
- Why agreement matters
- How this feeds the pipeline

Don't get lost in the clinical details. Use the vignette, then move on.

---

## Concepts to Include

- IRR (inter-rater reliability) — explain simply
- Gold-standard dataset
- Operational definition
- Ceiling effect (AI can't exceed human agreement)
- Pilot → validation → scale
- Falsifiability (IRR can fail)

## Concepts to Avoid

- Deep Bowen jargon (differentiation, triangles as primary frame)
- ML/AI technical details
- Overpromising on timeline
- Claiming results we don't have yet

---

## Soft Promotion Points

- **Pro App:** Available now, SARF built in
- **App Seminar:** Monthly practice with real cases
- **Personal App:** Coming soon, AI-powered intake
- **Open Source:** Both repos public on GitHub

---

## Vertical Alignment: Computer Science Principles

**One simple coding form gives you everything for free.**

When humans code using the SARF editor's structured form, the entire system aligns:

### What You Get

1. **Direct AI comparison** — Human coding produces the same structured output AI must produce. Apples-to-apples comparison.

2. **Real-time coding during audio** — The data model is a stream of deltas (changes), not a final document. A model can code a diagram in real-time as an interview unfolds.

3. **Stats on structured data** — Every field is defined, every relationship typed. Run any statistical analysis without scraping or transformation.

4. **Scalable IRR methodology** — Blind coding, agreement calculation, case management—all built in. The methodology is the infrastructure.

5. **Replicable study** — Same protocol, same tools, same data format. Anyone can replicate.

6. **Growing ground truth database** — Every curated, accepted case becomes part of the gold standard. The database grows over time, standardizing SARF.

7. **Infinite scaling** — Add coders, add cases, add languages. The infrastructure doesn't change.

8. **Same database across apps** — Pro app, Personal app, and research all use the same schema. Cases flow between contexts.

### The Computer Science Principle

Conventional research methods treat data collection, analysis, and application as separate problems. Each study builds its own instruments from scratch.

Computer science design treats them as one integrated system. Define the data model once; everything else follows. This is why technology companies can scale to billions of users while academic labs struggle with dozens of cases.

**Key line:** "Design the data model right, and everything else falls into place."

---

## Getting Involved (Brief Nod)

*Full pitch comes in the final presentation. This is just a nod.*

This infrastructure needs people:

- **Clinicians** — Test the clinical model, use the apps, provide feedback
- **Researchers** — Participate in IRR studies, contribute cases
- **Developers** — Open source repos, contribute to the tools

More on this at the end of the day.

---

## Connection to Day's Arc

**Presentation 1 (Why Family):** The field is broken, no measurement
**Presentation 2 (SARF Intro):** Here's a minimal framework
**Presentation 3 (This one):** Here's how to actually test it

This presentation is the "how" after the "why" and "what."
