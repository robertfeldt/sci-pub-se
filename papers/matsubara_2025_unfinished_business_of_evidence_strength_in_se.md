# The unfinished business of evidence strength in software engineering: Current practices and future directions

Matsubara PGF, Conte T. *Empirical Software Engineering* 31:4 (2026; published online 29 October 2025). https://doi.org/10.1007/s10664-025-10728-9. Data on Figshare: https://doi.org/10.6084/m9.figshare.27448440.v1

## TLDR
- **Question:** almost 20 years after Dybå & Dingsøyr (ESEM 2008) introduced evidence strength and GRADE to SE, how do SE secondary studies actually assess the strength of evidence, and do they make (and grade) recommendations to practitioners?
- **Method:** tertiary study. Automated search (Scopus, ACM, IEEE, Compendex) for "strength of evidence"-type terms and CERQual, plus forward snowballing of Dybå & Dingsøyr 2008a. 1,116 papers screened; final set of **22 secondary studies** that claim a strength assessment.
- **Uptake is low:** of 74 SE systematic reviews citing Dybå & Dingsøyr (among 94 passing the first filter), only 12 attempted to assess strength of evidence.
- **Methods used (RQ1):** GRADE in 10 papers (45%), all citing the **2004 version** despite the 2008 and 2011 updates; GRADE-CERQual in 1; evidence hierarchies in 2; quality of primary studies only in 6; no method in 3. Nine of the 22 are systematic mapping studies, a review type strength assessment isn't meant for.
- **Method rarely fits review type:** only 2 of 22 did: Ali et al. 2010 (quantitative review of aspect-oriented programming, using GRADE) and Matsubara et al. 2023 (qualitative review of expert effort estimation, using GRADE-CERQual).
- **How assessments are done (RQ2):**
  - 20 of 22 rate *all findings together* generically; only 2 assess each review finding separately, as GRADE and CERQual require.
  - Most GRADE users copy Dybå & Dingsøyr's four components (study design, quality, consistency, directness) and omit imprecision and publication bias; some treat study design as a component rather than as GRADE's starting point.
  - Six papers **confuse quality assessment of primary studies** (e.g. Ivarsson & Gorschek's rigour/relevance instrument, Dybå & Dingsøyr's checklist) **with strength of a body of evidence**.
  - Some assessments are partial, e.g. mentioning only consistency, or simply saying "similar to Dybå & Dingsøyr: very low".
- **Recommendations (RQ3):** 18 of 22 give no explicit recommendations. Only 2 derive specific recommendations from their findings, and **none assess the strength of recommendations** (benefits vs harms, stakeholder values, resources), which is the second half of GRADE.
- **Why it is hard in SE:**
  - Lack of standard outcomes. They suggest something like medicine's "core outcome sets".
  - Findings are often vague or implicit.
  - Mostly observational data, which raises the question whether GRADE's rating-up criteria even apply.
  - Kitchenham et al.'s "skill factor" and "lifecycle issue": SE interventions depend on practitioner expertise and affect only part of the lifecycle.
  - No SE equivalent of medical societies that issue guidelines. Are practitioners like physicians using guidelines, or like patients being advised?
- **Prior SE guidance they build on:** Kitchenham et al. 2015 (evidence ladder for SE study types, from feasibility studies to randomised field experiments); SEGRESS reporting guideline (Kitchenham et al. 2022); Budgen et al. 2020 (few reviews give guidance usable for teaching SE practice); Evidence Briefings (Cartaxo et al. 2016).
- **Critiques of GRADE they acknowledge:** weak theoretical and empirical justification for some components; vague terminology; high time and resource cost; the "cookbook medicine" criticism of rigid, uniform guidelines. Training does improve agreement between raters.
- **Call to action, if used "as is":** pick the method that fits the review type; use the latest version and all its components; write explicit, specific findings (or organise them by outcome); don't equate study quality with evidence strength; assess each finding separately; base recommendations on evidence and grade them.
- **Or adapt, or build something new:** decide whether an evidence hierarchy makes sense for SE at all, and justify SE-specific criteria for rating down and up. GRADE and CERQual are offered as starting points to adopt, adapt or critique, not to adopt blindly.
