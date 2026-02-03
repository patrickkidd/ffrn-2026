# Presentation 3: Clinical Research at the Cutting Edge

## Slide Deck Draft (Low Resolution)

**Duration:** 45 minutes (11:15-12:00)
**Format:** Conversational, room for questions and discussion

---

## SECTION 1: CONNECTING TO THIS MORNING (5 min)

---

### Slide 1: Title

**Clinical Research at the Cutting Edge**
*How do we actually test whether any of this works?*

Dr. Patrick Stinson
Alaska Family Systems

---

### Slide 2: This Morning's Problem

**The field lacks measurement.**

- Practices spread without validation
- No way to know if clinical evaluation is accurate
- No way to compare across practitioners

*So how do we research this?*

---

## SECTION 2: THE SCALING PROBLEM (10 min)

---

### Slide 3: Big Data vs. Small Data

| Big Data | Small Data |
|----------|------------|
| Millions of records | Rich qualitative information |
| Simple variables | Requires interpretation |
| Machine-readable | Requires intelligent inference |
| Insurance claims, lab results | Clinical interviews, family history |

*Our problem is small data.*

---

### Slide 4: The Coding Problem

To test SARF, someone has to code cases:
- Read/listen to clinical interviews
- Identify shifts in S, A, R, F
- Record them on a timeline

**Previously:** Humans doing this tediously, by hand.

---

### Slide 5: Why This Research Never Happened

- Hypothetical model with simple but deep concepts
- Requires skilled human coders
- Coding doesn't scale
- Can't get funding or momentum unless it's someone's day job

*The bottleneck was human coding capacity.*

---

### Slide 6: What Changed

**Machine automation now makes intelligent inference possible at scale.**

- Generate synthetic clinical discussions for training
- Test automated coding against human judgment
- Iterate faster than ever before

*We built this.*

---

## SECTION 3: DOMAIN-EXPERT GROUND TRUTH (10 min)

---

### Slide 7: Ground Truth

**Ground truth = what the domain experts agreed on.**

1. Train human experts on SARF
2. Have them code cases independently (blind)
3. Measure agreement (Inter-Rater Reliability)
4. Cases where they agree = ground truth

*The humans set the standard.*

---

### Slide 8: Why Ground Truth Matters

**The machines don't decide what's correct. Humans do.**

- Software learns to replicate human expert judgment
- Every output can be reviewed and corrected
- Domain experts remain the authority

*Ground truth is human truth.*

---

### Slide 9: The Infrastructure

[SCREENSHOT: IRR app interface]

We built a web-based system:
- Case management
- Blind coding workflow
- Agreement statistics

---

## SECTION 4: DISCOVERIES (10 min)

---

### Slide 10: Modeling Clinical Discussion

To train humans and test software, we needed data.

**Solution:** Generate synthetic clinical discussions.
- Realistic scenarios
- SARF-codeable content
- Controlled environment for training

---

### Slide 11: Discovery — Mutual Discovery

**You can't survey for this data like a knee problem.**

The therapist must be in a process of *mutual discovery* with the client.
- Not extracting answers
- Exploring together
- The relationship affects what emerges

*If you just interrogate, you don't get the data you need.*

---

### Slide 12: Discovery — Synthetic Data Trains Faster

The working group learned SARF coding faster on synthetic data than real cases.

- Cleaner examples
- Known ground truth
- Faster iteration

*Real recordings are the goal. Synthetic data accelerates getting there.*

---

### Slide 13: The Responsibility Pattern

Two 45-minute interviews. Person sees for the first time:

- Pattern of constantly picking up responsibility
- Saying yes to everything, no filter
- Anxiety going up and up
- **No downs.**

*Just seeing the data organized was the breakthrough.*

---

## SECTION 5: WHAT BECOMES POSSIBLE (5 min)

---

### Slide 14: If This Works

**Certification**
- Objective competency testing
- Compare trainee coding to ground truth

**Standardized Training**
- Measurable outcomes
- Curriculum based on validated method

**Aggregate Research**
- Data across practitioners
- Statistical patterns emerge

---

### Slide 15: More Concrete Than...

This is more concrete than anything this professional network has produced in decades.

- A minimal data model (SARF)
- A method to test agreement (IRR)
- Infrastructure to establish ground truth
- A path to scale

---

## SECTION 6: HONEST STATE (5 min)

---

### Slide 16: Where We Are

**Early stage. Showing the process.**

- First IRR meeting: next week
- Synthetic data: working
- Real recordings: exploring

*This is what real R&D looks like.*

---

### Slide 17: The Human Remains Central

- Ground truth is set by domain experts
- Software replicates human judgment
- Every output reviewable and correctable

*Technology scales. Humans validate.*

---

### Slide 18: Tools

| Tool | Status |
|------|--------|
| **Pro App** | Released — timeline + diagram |
| **Personal App** | In development — structured intake |
| **IRR System** | In use — research infrastructure |

alaskafamilysystems.com

---

### Slide 19: Questions & Discussion

**Dr. Patrick Stinson**
Alaska Family Systems
patrick@alaskafamilysystems.com

---

## NOTES FOR PRESENTER

### Timing Guide

| Section | Slides | Time |
|---------|--------|------|
| Connecting to morning | 1-2 | 5 min |
| The Scaling Problem | 3-6 | 10 min |
| Domain-Expert Ground Truth | 7-9 | 10 min |
| Discoveries | 10-13 | 10 min |
| What Becomes Possible | 14-15 | 5 min |
| Honest State + Close | 16-19 | 5 min |

**Total: ~40 minutes, leaving room for questions throughout**

### Screenshot Needed

- IRR app interface (Slide 9)

### Key Concepts Introduced

- **Big data vs. small data** — why this problem is hard
- **Ground truth** — human experts set the standard
- **Synthetic data** — accelerates training, real recordings are the goal
- **Mutual discovery** — clinical interview isn't a survey

### Key Lines

- "Ground truth is human truth"
- "The machines don't decide what's correct. Humans do."
- "Technology scales. Humans validate."
- "If you just interrogate, you don't get the data you need."
- "Just seeing the data organized was the breakthrough."

### Framing

**Low-resolution overview.** Don't get into technical nuts and bolts—we did it, here's what we learned. Leave room for:
- Questions throughout
- Discussion at end
- Ideas to breathe

The story: We built research infrastructure. We made discoveries. Here's where it leads.
