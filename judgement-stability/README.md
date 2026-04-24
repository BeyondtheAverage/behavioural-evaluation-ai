# When Judgement Does Not Stay the Same

When Judgement Does Not Stay the Same
Stability and Variation in Repeated AI Evaluation

This repository accompanies the working paper:

Hull, I. (2026). When Judgement Does Not Stay the Same: Stability and Variation in Repeated AI Evaluation. Beyond the Average Research Series.

The project examines how AI judgement changes when the same evaluative task is repeated under controlled conditions. Rather than treating variation as noise or error, the paper explores how instability appears in structured and predictable ways, particularly at decision boundaries.

Feedback and discussion are welcome via the Beyond the Average Substack.

Overview

AI systems are commonly evaluated through single outputs, where reliability is inferred from whether a response appears reasonable, unbiased, or well explained.

However, language-based AI systems generate responses probabilistically. When the same task is repeated, the resulting judgements do not always remain the same.

This paper focuses on what happens when identical inputs are evaluated multiple times. It examines where judgements remain stable, and where they begin to vary.

The central finding is that variation is not random. It is concentrated at decision boundaries, where interpretation is required.

Key Idea

Repetition does not introduce instability.
It reveals whether a judgement is stable.

Research Context

This work builds on the Behavioural Evaluation Framework for AI Judgement Systems (Hull, 2026), which proposes evaluating AI behaviour through:

repeated execution
internal signals
independent system comparison

Within that broader framework, this paper isolates one specific dimension:

judgement stability under repeated execution

The analysis draws on experiments from the Agents at Work research series, examining how AI systems classify job advertisements for potential age-coded language.

Findings

Repeated evaluations reveal distinct behavioural patterns:

High overall stability
Most classifications remain consistent across runs
Meaningful variation
A minority of cases produce different outcomes under identical conditions
Boundary concentration
Variation occurs primarily between adjacent categories such as
“Potentially Biased” and “Unclear”
Stable reasoning, different decisions
Explanations often remain similar even when classifications change

These findings indicate that instability reflects structured sensitivity to interpretation, rather than random error.

Repository Contents

This repository contains materials related to the paper and supporting experiments.

Typical contents may include:

paper/
When_Judgement_Does_Not_Stay_the_Same.pdf
experiments/
Notebooks and scripts for repeated evaluation testing
data/
Sample job advert inputs used in the study
figures/
Visualisations of stability, variation, and decision boundaries
Conceptual Summary

The paper introduces a behavioural lens on AI judgement:

Stable cases occur where signals are clear
Variation emerges where interpretation is required
Decision boundaries act as zones of sensitivity

As illustrated in the paper (Figure 1), variation appears within a narrow “boundary zone” between adjacent classifications rather than across the full range of outcomes

This reframes instability as a property of the system’s decision process, not simply a failure of accuracy.

Implications

Evaluation approaches that rely on single outputs may:

overlook structured variation
overestimate reliability
miss sensitivity at decision boundaries

In real-world applications, this matters most in borderline cases, where small differences in interpretation can lead to different outcomes at scale.

Citation

If you reference this work, please cite:

Hull, I. (2026).
When Judgement Does Not Stay the Same: Stability and Variation in Repeated AI Evaluation.
Beyond the Average Research Series. Working Paper.

Author

Imogen Hull
Independent Researcher – AI Behaviour & Reliability
Beyond the Average Research Series

Licence

This project is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence.

See the LICENSE file for details.

If you want, I can tighten this further into a slightly more “GitHub-native” version (shorter, punchier) or expand it into a portfolio-ready repo with badges, visuals, and a positioning hook for recruiters or collaborators.

ok i have the repository and i have the two pdfs loaded up there. the trouble is the readme references the first one. can i update the readme to go to separate readmes for each paper within the repository?

Yes – and you should. What you have now (one README pointing to one paper) will start to feel cramped as soon as you add more work. The clean way to handle this on GitHub is a layered README structure.

Here’s how to do it without overcomplicating things.

The structure that works best

Keep one main README at the root, then give each paper its own folder with its own README.

repo/
│
├── README.md                ← main landing page
│
├── behavioural-framework/
│   ├── README.md            ← paper-specific README
│   └── Behavioural_Framework.pdf
│
├── judgement-stability/
│   ├── README.md            ← paper-specific README
│   └── When_Judgement_Does_Not_Stay_the_Same.pdf
│
├── experiments/
├── data/
└── figures/
What changes in practice
1. Your main README becomes a hub, not a paper page

Instead of describing one paper in full, it briefly introduces your work and links out.

Example:

Beyond the Average Research Series
Behavioural Evaluation of AI Systems

This repository contains working papers and supporting materials exploring how AI systems behave under repeated evaluation.

The work focuses on judgement stability, variation, and behavioural reliability in language-based AI systems.

Papers
1. Behavioural Evaluation Framework for AI Judgement Systems

Introduces the core framework for behavioural evaluation.
→ View paper and materials

2. When Judgement Does Not Stay the Same

Examines stability and variation under repeated execution.
→ View paper and materials

About

Imogen Hull
Independent Researcher – AI Behaviour & Reliability

Licence

CC BY 4.0

2. Each paper gets its own full README

This is where you paste the detailed write-ups (like the one I just created for you).

So:

/behavioural-framework/README.md → your existing framework write-up
/judgement-stability/README.md → the new one we just drafted
Why this is better (and actually important for you)

This isn’t just tidiness – it directly supports your positioning:

1. Each paper becomes independently shareable

You can link directly to a paper folder on:

LinkedIn
Substack
ORCID
Zenodo

And it looks complete on its own.

2. It matches how your work is evolving

You’re no longer writing “one paper” – you’re building a research series.

This structure quietly signals:

continuity
depth
credibility
3. It avoids rewriting the README every time

You just:

add a new folder
add a new link

Done.

One small but important detail

Use relative links like this:

[View paper](./judgement-stability/)

Not full URLs – this keeps everything portable if you rename or move the repo.

Optional (but powerful, given your work)

Later, you can add:

README.md badges (license, version)
a simple “Research Themes” section (stability, confidence, drift, etc.)
links to your Substack or working paper DOI

But don’t do that yet – your current priority is clarity and structure.

Bottom line

Yes – split it.

Think of your repo as:

a library, not a document.

The main README is the front desk.
Each folder is a paper on the shelf.

If you want, I can:

restructure your existing README into the hub version, or
format both paper READMEs so they feel consistent as a “series”

That’s where it starts to look properly professional.

how do i set up a new folder and move it

You’re very close – GitHub just hides the “folder” concept a bit, which makes this feel harder than it is.

Here’s the simplest way to do it directly in the GitHub UI (no coding needed).

Step 1 — Create a new folder

GitHub doesn’t have a “New Folder” button.
You create a folder by creating a file inside it.

Do this:
Click “Add file” → “Create new file”
In the filename box, type:
judgement-stability/README.md
Add a simple placeholder (e.g. # When Judgement Does Not Stay the Same)
Scroll down → Commit changes

✅ This creates:

a folder: judgement-stability
a file inside it: README.md
Step 2 — Move your PDF into the folder

GitHub also doesn’t have a drag-and-drop “move” button.
You “move” a file by renaming its path.

Do this:
Click your file:
“When Judgement Does Not Stay the Same.pdf”
Click the ✏️ Edit (pencil icon)
In the filename box, change it to:
judgement-stability/When Judgement Does Not Stay the Same.pdf
Commit changes

✅ Now the PDF is inside the folder

Step 3 — (Optional) Do the same for your framework paper

Repeat:

behavioural-framework/README.md
behavioural-framework/Your_Framework_Paper.pdf
Step 4 — Update your main README (important)

Replace your current long write-up with a hub like this:

# Behavioural Evaluation AI

This repository contains working papers from the Beyond the Average Research Series, exploring how AI systems behave under repeated evaluation.

---

## Papers

### Behavioural Evaluation Framework for AI Judgement Systems  
→ [View paper](./behavioural-framework/)

### When Judgement Does Not Stay the Same  
→ [View paper](./judgement-stability/)

---

## Author  
Imogen Hull  
Independent Researcher – AI Behaviour & Reliability
What your repo will look like after

Instead of everything flat:

PDF
PDF
README

You’ll have:

README.md  ← hub

behavioural-framework/
    README.md
    paper.pdf

judgement-stability/
    README.md
    paper.pdf
One small tip (this matters for polish)

Rename your PDF slightly to remove spaces:

when-judgement-does-not-stay-the-same.pdf

It avoids messy links later.

If you want next step

I can:

format your two inner READMEs so they match as a “series”
or make your repo look like a proper research portfolio (very close to publishable standard)

You’ve already done the hard part – this is just presentation now.
