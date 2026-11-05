# A method for evaluating rigor and industrial relevance of technology evaluations

Ivarsson M, Gorschek T. *Empirical Software Engineering* 16(3):365–395, 2011 (online 6 Oct 2010). https://doi.org/10.1007/s10664-010-9146-4 (summary only; not open access).

## TLDR
- **Problem:** SE is an applied field, so research results should reach industry. Practitioners deciding whether to adopt a technology need evidence from realistic evaluations, and researchers need enough reporting to synthesise or replicate. Both are often missing.
- **Model:** score each technology evaluation on two dimensions with simple rubrics. The aim is an approximate overview of a research area, not a precise grade for each paper.
  - **Rigor (0–3)** scores how well rigor-related aspects are *reported*, not whether the study was actually done rigorously. Each aspect is weak (0), medium (0.5) or strong (1):
    - **Context:** described well enough that a reader can compare it with another context (development mode, time-to-market pressure, company maturity, etc.).
    - **Study design:** variables, controls, treatments and sampling described, not just "ten students did step 1, step 2 and step 3".
    - **Validity:** threats discussed in detail, by type (conclusion, internal, external, construct), with the measures taken to limit them.
  - **Relevance (0–4)** scores the realism of the evaluation. Each aspect counts 1 or 0:
    - **Subjects:** industry professionals (students, researchers or unstated subjects score 0).
    - **Context:** an industrial setting rather than a lab.
    - **Scale:** industrial-scale applications (toy examples and down-scaled systems score 0).
    - **Research method:** one that studies real situations, such as action research, lessons learned, case study, field study, interviews or descriptive surveys. Lab experiments and conceptual analysis score 0.
- **Validation:** a systematic review of requirements engineering (RE) technology evaluations in the ISI-listed SE journals. The search found 3,593 papers, 455 passed title/abstract screening and 349 were included and scored.
- **Findings:**
  - Most RE evaluations lack both rigor and relevance. 116 papers (about a third) score 0 on both, typically a toy example worked through by the researchers.
  - Only 6 of the 349 reach the top level on both dimensions. About 10% have the highest rigor and 15% the highest relevance.
  - Average rigor doubled from about 0.5 in the 1990s to about 1 in the 2000s, which is still low. Average relevance did not improve, even though the number of evaluations grew.
  - Venues differ a lot. EMSE stands out on rigor. TSE and TOSEM score low on both. Page-limited magazines (IEEE Software, Computer) score low on rigor: "the first thing to go" is the description of the study.
- **Model evolution:** applying the model made it *simpler*. The original version had more detailed aspects, but almost no papers reported them, so the rubric was cut to what papers actually report.
- **Limitations stated by the authors:** it scores the presentation, not the research; it ignores the results (a top-scoring study may report negative results); it does not judge whether the design fits the research questions; and a researcher applying a technology to industry data counts as a "researcher" subject, which can understate practical value.

## Teaching hooks
- Rigor here is a *reporting* score. Reporting context, design and validity well can raise it without running a new study. Score your own paper: which half-point could you gain just by writing better?
- The relevance rubric is the SE version of Cartwright's "worked there vs will work here": student subjects on toy examples in a lab score 0.
- A per-study quality score is not certainty in a finding. GRADE and CERQual add inconsistency, indirectness, imprecision and publication bias across the whole body of evidence.
- The rubrics build on rubrics previously used to assess SE master's theses (Feldt et al. 2009).
- Venue matters for what gets reported: compare the page limits of conference papers with journal papers.
