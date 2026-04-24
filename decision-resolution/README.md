# When a Decision Does Not Resolve  
### Non-resolution and Persistent Indeterminacy in AI Judgement Systems  

This repository accompanies the working paper:

**Hull, I. (2026). _When a Decision Does Not Resolve: Non-resolution and Persistent Indeterminacy in AI Judgement Systems_. Beyond the Average Research Series.**

The project examines a distinct behavioural pattern in AI judgement systems: cases where outputs remain stable under repeated evaluation, but do not resolve into a definitive classification.

Rather than variation or error, the paper identifies **persistent non-resolution** as a structured and observable property of AI behaviour.

Feedback and discussion are welcome via the Beyond the Average Substack.

---

## Overview  

AI systems are often evaluated based on whether their outputs appear reasonable, consistent or well explained. More recent approaches extend this by examining how outputs behave when the same task is repeated.

Where variation appears, this is typically interpreted as instability.

This paper identifies a different pattern.

In some cases, the system does not vary across repeated runs, but nor does it resolve its judgement. Instead, it consistently returns an indeterminate outcome.

The analysis focuses on what happens when AI systems encounter weak or ambiguous signals and are unable to commit to a classification.

---

## Key Idea  

Stability does not guarantee resolution.  
A judgement can remain consistent without becoming decisive.

---

## Research Context  

This work builds on the *Behavioural Evaluation Framework for AI Judgement Systems* (Hull, 2026), which proposes evaluating AI behaviour through:

- repeated execution  
- internal signals  
- independent system comparison  

Earlier work examined how judgements vary under repeated evaluation, particularly at decision boundaries.

This paper extends that line of enquiry by examining cases where:

- variation does not occur  
- resolution is also absent  

The analysis draws on the *Agents at Work* research series, focusing on how AI systems interpret age-coded language in recruitment text.

---

## Findings  

Repeated evaluation reveals a distinct behavioural pattern:

- **Persistent “Unclear” classification**  
  A subset of inputs is consistently classified as indeterminate across all runs  

- **Absence of variation**  
  No movement between categories, even under repeated execution  

- **Stable confidence behaviour**  
  Confidence remains moderate and tightly clustered, without increasing over time  

- **Contrast with boundary instability**  
  Other inputs fluctuate between categories, while these remain fixed but unresolved  

These findings indicate that non-resolution is not instability, but a separate behavioural mode.

---

## Repository Contents  

This repository contains materials related to the paper and supporting experiments.

Typical contents may include:

- `paper/`  
  `when-a-decision-does-not-resolve.pdf`  

- `experiments/`  
  Notebooks and scripts for repeated evaluation  

- `data/`  
  Sample job advert inputs used in the study  

- `figures/`  
  Visualisations of stability, variation and non-resolution patterns  

---

## Conceptual Summary  

The paper introduces **non-resolution** as a behavioural property of AI systems:

- Some cases vary under repeated evaluation (instability)  
- Some cases remain stable and resolve clearly  
- Some cases remain stable but **do not resolve at all**  

This third pattern reflects:

- detection of relevant signals  
- insufficient weight to cross decision thresholds  
- persistent indeterminacy  

As shown in the paper, early-career job adverts containing terms such as “junior”, “graduate” or “trainee” consistently produce “Unclear” classifications across repeated runs :contentReference[oaicite:0]{index=0}  

This reframes stability as insufficient on its own. A stable output may still represent an unresolved judgement.

---

## Implications  

Evaluation approaches that focus only on variation may:

- overlook persistent indeterminacy  
- misinterpret stability as reliability  
- miss cases where the system fails to commit  

In practice, this matters in borderline decision contexts, where a system may appear consistent but does not provide a usable outcome.

Reliability therefore depends not only on whether a judgement remains consistent, but whether it resolves into a meaningful classification.

---

## Citation  

If you reference this work, please cite:

Hull, I. (2026).  
_When a Decision Does Not Resolve: Non-resolution and Persistent Indeterminacy in AI Judgement Systems._  
Beyond the Average Research Series. Working Paper.

---

## Author  

**Imogen Hull**  
Independent Researcher – AI Behaviour & Reliability  
Beyond the Average Research Series  

---

## Licence  

This project is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** licence.

See the LICENSE file for details.
