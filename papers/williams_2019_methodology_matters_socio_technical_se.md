# Methodology Matters: How We Study Socio-Technical Aspects in Software Engineering

Williams C, Storey M-A, Ernst NA, Zagalsky A, Kalliamvakou E. arXiv:1905.12841, 2019 (preprint formatted for ACM TOSEM). A later, extended version appeared as Storey, Ernst, Williams & Kalliamvakou, "The who, what, how of software engineering research: a socio-technical framework", *Empirical Software Engineering* 25:4097–4129 (2020), https://doi.org/10.1007/s10664-020-09858-z

## TLDR
- **Question:** does SE research, at the community level, use methods that capture the *human and social* side of a socio-technical discipline?
- **Two-phase study:**
  - (1) Categorisation of 253 ICSE technical-track papers (from three years) by research strategy and data source.
  - (2) A survey of their authors (60 responses, 24%) on why they chose their methods and how they triangulate.
- **Framework:** Runkel & McGrath's research strategies (as in the ABC framework: generalisability vs control vs realism), plus a new **Data quadrant** for computational studies on trace data, which other frameworks lack.
- **Findings:**
  - 77% of the papers use *data strategies* (mining, computational experiments, simulations); 82% use *trace measures* (logs, repositories, Stack Overflow). Only about 20% use self-reports or observations of people.
  - Only 19% use more than one research strategy, and 21% more than one data source. Most papers do not triangulate within the paper.
  - Authors prioritise **generalisability and realism over control** of human behaviour, sometimes out of convenience ("just because data is convenient…") or to satisfy reviewers.
  - **Reviewer pressure:** authors say generalisability is what reviewers "easily criticise", which pushes towards large samples and away from controlled or naturalistic human studies.
  - **Triangulation knowledge gap:** 17 of 60 authors did not know what triangulation means in research (11 of them were students).
- **Recommendation:** diversify the community's methods, with more studies that directly involve developers, and triangulate across strategies and data sources.

## Teaching hooks
- Shows the ABC trade-off (S4 slides 7–9) at the *community* level: the choices of individual papers add up to a field skewed towards trace data.
- Reviewer behaviour shapes methods, which links to Lago et al.'s C10/C11 and Tuesday's reviewing seminar.
- Relevant for the IS and human-aspects participants: socio-technical questions need methods that study people, not only their traces.
- Question for the room: which quadrant does your study sit in, and what would a triangulating second study look like?
