# SARF Data Model White Paper

Dr. Patrick Stinson
Alaska Family Systems - alaskafamilysystems.com
2025-11-19

## Purpose

SARF is a qualitative, timeseries data model for clinical evaluation and research. It simplifies the complexity of relationships in mental health issues into a minimum testable method for collecting data. It is not intended to be a comprehensive model out of the gate, but is intended to be 100% data-driven and to increase in detail and precision as evidence permits.

SARF organizes the collection of qualitative data to test both a single hypothesis for a single clinical case, and to test a generalizable hypothesis in formal experimental research.

## Audience

This document is intended for anyone who might apply it. This is meant to be the materials that you provide someone the first time you mention it, so they can learn more.

## Summary

*SARF stands for Symptom, Anxiety, Relationship, Functioning. The basic clinical hypothesis is that episodic (S)ymptoms in an individual are modulated by acute shifts in (A)nxiety, which are modulated by shifts in the (R)elationship system. Durable shifts in symptoms are associated with shifts in the level of chronic anxiety. Clinical change involves increasing (F)unctioning through all the usual means, which decreases the impact of R on A, and so also S. R subdivides into at least the short-term strategies of conflict, distance, reciprocity, projection, cutoff, and triangling, and the more sophisticated long-term innovative strategy "define self."*

*Interactions between these variables are more complex than a simple pipeline. The goal here is to provide a simple, straightforward starting point for medical and mental health clinicians and people in the helping professions. A and R are to be ruled out as impacting S in a differential diagnosis. The model does not imply that all symptoms work this way, which would be bad scientific practice. F is the independent clinical variable, where higher functioning should lessen the impact of A and R on S. The goal is to "function up."*

## Origin

Havstad & Sheffield first defined this model in 2018 as the "Framework for Clinical Research based on Bowen theory." I have shortened and operationalized it to SARF for professional and research and development, formal clinical application, systematic inner-rater reliability (IRR) research, or training AI models on real case data.

## Application

Collect a timeline of shifts in each variable in a clinical assessment interview. Clinically you ought to be able to collect them for every case as a "timeline of nodal events." Training is required to be able to conduct a good assessment interview that gathers the context variables of A and R. Once the timeline is collected, it is evaluated for stand-out correlations between the variables with S. There is currently no more formalized predictive model to evaluate the correlations in time, though this is the goal.

As with all evidence based practices, the hypothesis of this model is re-tested in each clinical case. In medical terms, SARF is used in a differential diagnosis to rule out the impact of the (A)nxiety, and (R)elationship variables from (S)ymptoms.

## Definitions

The etiological pipeline consists of R -> A -> S. The independent clinical variable is F. Etiological pipeline means the technical explanation for what makes and modulates symptoms.

### S: Symptom

Symptoms are simple enough. They are the problems that bring people in to see clinicians. They encompass the entire range of mental, behavioral, emotional, and psychiatric diagnoses. They also include many medical symptoms, especially chronic and more complex or difficult to predict issues like auto-immune, allergies, cancers, etc.

Value space: up, down, same

### A: Anxiety

Anxiety is synonymous with autonomic threat response. Threat response is determined by perceived threat. While determined by perception, it is deeply biological and evolutionarily very, very old. This is why it impacts both behavioral/emotional symptoms and so many physiological symptoms.

Value space: up, down, same

### R: Relationship

Value space: conflict, distance, reciprocal functioning, child-focus, cutoff, inside (triangle), outside (triangle), defined-self.

Relationship shifts are automatic moves that a person makes in relation to one or more other people. "Automatic" means that it was driven by emotion, without choice, often with short-term motivation versus long-term thoughtfulness.

### F: Functioning

Value space: up, down, same

Function is how well balanced emotion and thinking is towards the person's goals, defined/stated when they are at their calmest. When functioning is low, a person is ruled by emotion and unable to utilize their intellect to plan, problem solve, see the forest for the trees.

## Development

SARF is intended to scale in both complexity and precision. Complexity in that each variable would certainly sub-divide into pieces as time goes on. Precision in that each piece would be more precise than before the division and would add nuance to the total SARF pie.

The principle here is like NIH's RDoC, which began as the minimum categories required to capture data to actually test hypotheses in a formal way. As more is learned, more categories or variables are added to add nuance and precision. Further, the categories are used to organize a network of experimental literature about the concepts and variables.

The NIH announced RDoC two weeks before the publication of the DSM 5 in 2013, along with the cancelation of all funding for research exclusively guided by the DSM. The rationale for this was that the DSM suffers from low scientific validity. RDoC was NIH's answer for the minimum framework that could at least orgnanize testable hypotheses, i.e focused on validity.

Similarly, SARF is aimed at being the minimal framework for collecting data on the impact of relationships on individual symptomology.

## Tools & Programs

- There is an R&D effort to manually code cases with SARF as an inter-rater reliability (IRR) study. A web-based app is built to manage thousands of cases and conduct blind domain-expert SARF coding of those cases. Domain-experts will be recruited to code cases themselves to increase the sample size.
- If sufficient IRR is achieved. An AI model will be trained to automatically code interviews using the data from the IRR study.
- These variables are built-in to the existing Family Diagram "Pro' app where you visualize their shifts on the family diagram over time.
- The AI model will provide an engine for the "Personal" mobile self-help app currently in development. This app will generate the timeline and family diagram by chatting with the client/patient. It can then also be used as an intake tool for the "Pro" Family Diagram app which is already released, since the pro version can open the case file from the personal version.
