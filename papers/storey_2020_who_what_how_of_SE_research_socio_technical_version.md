# The who, what, how of software engineering research: a socio-technical framework

Storey M-A, Ernst NA, Williams C, Kalliamvakou E. *Empirical Software Engineering* 25(5):4097–4129, 2020. https://doi.org/10.1007/s10664-020-09858-z. Replication package: https://doi.org/10.5281/zenodo.3813878. Journal-first at ESEM 2021. Reworked and extended from the 2019 preprint "Methodology Matters" (Williams et al., arXiv:1905.12841, 253 ICSE papers + author survey); the data and numbers below are from the EMSE version.

## TLDR
- **Question:** SE is socio-technical, so how much of our research is aimed at people, and how much of it actually studies them?
- **The Who-What-How framework:**
  - **Who** benefits: human stakeholders (developers, managers, end users…), technical systems, or researchers. A paper can name several.
  - **What** is the main contribution (design-science lens): *descriptive* (understanding a problem or context) or *solution* (designing or evaluating an intervention).
  - **How** is it done: research strategies adapted from Runkel & McGrath, in four empirical quadrants:
    - *Field* (field study, field experiment), *Lab* (lab experiment, experimental simulation) and *Respondent* (sample survey, judgment study) all involve people directly.
    - *Data* (mining, computer simulation, in-silico evaluation) involves no human participants.
    - Plus non-empirical strategies (meta/SLR, formal theory).
  - Four quality criteria around the circumplex: *generalisability*, *realism*, *control* of human behaviour variables, and *precision* of system data. The last was added because so much SE research relies on precise tool-generated data. Every strategy trades these off, so you triangulate across quadrants.
- **Data:** all 151 papers from the ICSE 2017 technical track (68) and EMSE 2017 (83). Each paper was coded by at least two researchers, relying on the authors' own words.
- **Findings:**
  - **Who:** 76% (ICSE) and 77% (EMSE) claim their research may benefit human stakeholders, but humans are the *sole* beneficiary in only 15% (ICSE) and 27% (EMSE).
  - **What:** ICSE is 81% solution and 19% descriptive papers; EMSE 37% / 63%.
  - **How:** Data strategies dominate (71% of ICSE and 85% of EMSE papers), and over half of all papers use *only* data strategies. Field 5|5, Lab 13|7, Respondent 23|14 papers (EMSE|ICSE).
  - **The key mismatch:** **54% (ICSE) and 43% (EMSE) claim to benefit humans but never study humans directly**, relying on trace data instead.
  - Only 27% involve practitioners at all, sometimes just one or two in a small judgment study.
  - **Triangulation across quadrants is rare:** only 37 papers (about 25%) use more than one quadrant, usually data + a survey or interviews. *Data* triangulation (more datasets) is common, but it improves generalisability, not realism or control.
  - EMSE (a journal, often extending conference papers) did *not* show more triangulation than ICSE.
- **Why human-oriented strategies are rare (the authors' interpretation):**
  - SE researchers have data skills but lack social-science training.
  - Practitioner access is limited.
  - Reviewers easily attack low generalisability. The 2019 preprint's author survey found authors chasing generalisability because "that's what reviewers easily criticise".
  - Reviewers may expect internal/external/construct validity and treat qualitative criteria (credibility, transferability) as unfamiliar.
  - Ethics approval adds friction.
- **The downside of data-only studies:**
  - A tool evaluated only on historical data assumes developers will use it exactly as they used the old one.
  - Trace data misses context (Aranda & Venolia; the "promises and perils" of mining Git and GitHub).
- **Recommendation:** diversify and triangulate research strategies, especially for work that claims to benefit people. Use Who-What-How when *designing* a study, not only when classifying papers, and discuss how venue values and expectations shape the field's research.
- **Limitations:** two venues, one year (2017); coding relies on the authors' own wording; triangulation across a researcher's *other* papers is not visible.

## Teaching hooks
- **Three questions for any study, including participants' own:** *who* is meant to benefit, *what* kind of contribution is it, and does the *how* actually study those people? The 54%/43% "claims to help humans but never studies them" figure is the provocation.
- It turns the ABC framework (Stol & Fitzgerald, S4 slides 7–9) into a lens on the whole field, using the same Runkel & McGrath circumplex with a "Data" quadrant added.
- Leads into Storey et al. 2025 on mixed methods: how to triangulate properly. Their "selling your soul" antipattern is the reviewer pressure described here.
- Reviewer angle (Tue S3): reviewers who default to "low generalisability" criticism push the field towards data-only studies.
- Its introduction cites Feldt et al. 2008 on social aspects becoming increasingly critical in SE practice and research.
