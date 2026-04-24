# When Judgement Does Not Stay the Same  
### Stability and Variation in Repeated AI Evaluation 

This repository accompanies the working paper:

**Hull, I. (2026). _When Judgement Does Not Stay the Same: Stability and Variation in Repeated AI Evaluation_. Beyond the Average Research Series.**

The project examines how AI judgement changes when the same evaluative task is repeated under controlled conditions. Rather than treating variation as noise or error, the paper explores how instability appears in structured and predictable ways, particularly at decision boundaries.

Feedback and discussion are welcome via the Beyond the Average Substack.

---

## Overview  

AI systems are commonly evaluated through single outputs, where reliability is inferred from whether a response appears reasonable, unbiased or well explained.

However, language-based AI systems generate responses probabilistically. When the same task is repeated, the resulting judgements do not always remain the same.

This paper focuses on what happens when identical inputs are evaluated multiple times. It examines where judgements remain stable, and where they begin to vary.

The central finding is that variation is not random. It is concentrated at decision boundaries, where interpretation is required.

---

## Key Idea  

Repetition does not introduce instability.  
It reveals whether a judgement is stable.

---

## Research Context  

This work builds on the *Behavioural Evaluation Framework for AI Judgement Systems* (Hull, 2026), which proposes evaluating AI behaviour through:

- repeated execution  
- internal signals  
- independent system comparison  

Within that broader framework, this paper isolates one specific dimension:

**judgement stability under repeated execution**

The analysis draws on experiments from the *Agents at Work* research series, examining how AI systems classify job advertisements for potential age-coded language.

---

## Findings  

Repeated evaluations reveal distinct behavioural patterns:

- **High overall stability**  
  Most classifications remain consistent across runs  

- **Meaningful variation**  
  A minority of cases produce different outcomes under identical conditions  

- **Boundary concentration**  
  Variation occurs primarily between adjacent categories such as  
  _“Potentially Biased”_ and _“Unclear”_  

- **Stable reasoning, different decisions**  
  Explanations often remain similar even when classifications change  

These findings indicate that instability reflects structured sensitivity to interpretation, rather than random error.

---

## Repository Contents  

This repository contains materials related to the paper and supporting experiments.

Typical contents may include:

- `paper/`  
  `When_Judgement_Does_Not_Stay_the_Same.pdf`  

- `experiments/`  
  Notebooks and scripts for repeated evaluation testing  

- `data/`  
  Sample job advert inputs used in the study  

- `figures/`  
  Visualisations of stability, variation and decision boundaries  

---

## Conceptual Summary  

The paper introduces a behavioural lens on AI judgement:

- Stable cases occur where signals are clear  
- Variation emerges where interpretation is required  
- Decision boundaries act as zones of sensitivity  

As illustrated in the paper (Figure 1), variation appears within a narrow “boundary zone” between adjacent classifications rather than across the full range of outcomes.

This reframes instability as a property of the system’s decision process, not simply a failure of accuracy.

---

## Implications  

Evaluation approaches that rely on single outputs may:

- overlook structured variation  
- overestimate reliability  
- miss sensitivity at decision boundaries  

In real-world applications, this matters most in borderline cases, where small differences in interpretation can lead to different outcomes at scale.

---

## Citation  

If you reference this work, please cite:

Hull, I. (2026).  
_When Judgement Does Not Stay the Same: Stability and Variation in Repeated AI Evaluation._  
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
