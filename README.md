# Behavioural Evaluation of AI Judgement Systems  
### Beyond the Average Research Series  

This repository contains a series of working papers examining how AI systems behave when making evaluative judgements under repeated conditions.

The work moves from a general framework for behavioural evaluation to a set of focused studies exploring specific properties of AI judgement, including stability, confidence, explanation and resolution.

Rather than assessing individual outputs in isolation, the series examines how judgements behave over time.

---

## Structure of the Work  

The research is organised in two layers:

### 1. Behavioural Evaluation Framework  

**A Behavioural Evaluation Framework for AI Judgement Systems**

This paper introduces the core approach used throughout the series.

It proposes that AI systems should be evaluated through:

- repeated execution  
- internal signals (such as confidence or agreement)  
- comparison across independent systems  

The framework shifts evaluation from individual outputs to observable behavioural patterns.

→ See: `./behavioural-framework/`

---

## 2. Behavioural Studies  

The papers below apply the framework to specific aspects of AI judgement.

Each paper isolates a particular behavioural property observed in repeated evaluation.

---

#### When Judgement Does Not Stay the Same  
**Stability and variation in repeated evaluation**

Examines how AI judgements change under identical conditions.

Finds that variation is not random, but concentrated at decision boundaries where interpretation is required.

---

#### When a Decision Does Not Resolve  
**Persistent indeterminacy in AI judgement**

Identifies a distinct pattern where judgements remain stable but do not resolve into a definitive classification.

Shows that stability alone does not imply a usable decision.

---

#### When Explanation Does Not Stay the Same  
**Variation in reasoning across repeated outputs**

Explores how explanations shift across runs, even when the underlying judgement appears similar.

Shows that consistent reasoning cannot be assumed from a single explanation.

---

#### When Confidence Does Not Indicate Reliability  
**Confidence as a behavioural signal**

Examines how confidence behaves across repeated evaluation.

Finds that confidence does not reliably track stability or correctness, and should be interpreted as a behavioural signal rather than proof of reliability.
### 2. Behavioural Studies  

The papers below apply the framework to specific aspects of AI judgement.

Each paper isolates a particular behavioural property observed in repeated evaluation.

---

## Conceptual Progression  

Taken together, the papers describe a set of behavioural patterns observed in AI judgement systems:

- **Variation** – judgements change across repeated runs  
- **Explanation drift** – reasoning shifts while remaining plausible  
- **Confidence misalignment** – confidence does not reflect stability  
- **Non-resolution** – judgements remain stable but do not resolve  

These patterns extend evaluation beyond accuracy to include how systems behave under repetition, constraint and ambiguity.

---

## Key Position  

AI evaluation is often based on single outputs.

This work argues that:

> Reliability is not established by a single answer.  
> It must be observed through behaviour over time.

---

## Repository Contents  

The repository is structured as a set of paper-specific folders:

- `behavioural-framework/`  
- `judgement-stability/`  
- `explanation-stability/`  
- `confidence-behaviour/`  
- `non-resolution/`  

Each folder contains:

- the working paper  
- a dedicated README explaining the contribution  
- supporting materials where applicable  

---

## Author  

**Imogen Hull**  
Independent Researcher – AI Behaviour & Reliability  
Beyond the Average Research Series  

---

## Licence  

This work is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence.

See the LICENSE file for details.
