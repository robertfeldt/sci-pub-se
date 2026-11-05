# A method for evaluating rigor and industrial relevance of technology evaluations

Ivarsson M, Gorschek T. *Empirical Software Engineering* 16(3):365–395, 2011 (online 2010). https://doi.org/10.1007/s10664-010-9146-4 (summary only; not open access).

## TLDR
- **Problem:** SE research aims to help industry decide whether to adopt a technology, but primary studies differ widely in how well they report their evaluations, and in how close those evaluations are to real industrial use. Systematic reviews need a simple, comparable way to score both.
- **Two dimensions, scored separately:**
  - **Rigor** is about *reporting*: is enough described for a reader to judge and compare the study?
  - **Relevance** is about *industrial realism*: how close is the evaluation to the intended users and setting?
- **Rigor rubric (0–3).** Each aspect scores weak (0), medium (0.5) or strong (1):
  - **Context:** described well enough that a reader can compare it with another context (development mode, speed, company maturity, etc.).
  - **Study design:** variables, controls, treatments and sampling described, not just "ten students did step 1, step 2 and step 3".
  - **Validity threats:** discussed in detail, by type (conclusion, internal, external, construct), with the measures taken to limit them.
- **Relevance rubric (0–4).** Each aspect contributes 1 or 0:
  - **Users/subjects:** industry professionals, i.e. representative of the intended users.
  - **Context:** an industrial setting.
  - **Scale:** applications of realistic, industrial size, not toy examples.
  - **Research method:** one that studies real situations (action research, lessons learned, case study, field study, interviews, descriptive surveys). Laboratory experiments and conceptual analysis do not contribute.
- **Validation:** the authors apply the method to a systematic review of requirements engineering technology evaluations.
- **Use since then:** widely used to assess primary studies in SE systematic reviews and mapping studies, sometimes as is, sometimes adapted.

## Teaching hooks
- Scores *reporting* quality and *realism*, not whether the findings are true. A high-rigor study can still have low certainty once the body of evidence is considered (inconsistency, indirectness, imprecision): compare GRADE and CERQual.
- The relevance rubric is the SE version of Cartwright's "worked there vs will work here": student subjects on toy systems in a lab score 0.
- Exercise: score your own paper. Which point could you gain just by *reporting* better, without running a new study?
