# Threats to Validity in Software Engineering – hypocritical paper section or essential analysis?

Lago P, Runeson P, Song Q, Verdecchia R. *ESEM '24* (18th ACM/IEEE International Symposium on Empirical Software Engineering and Measurement), Barcelona, pp. 314–324, 2024. https://doi.org/10.1145/3674805.3686691. Open access (CC BY 4.0): https://robertoverdecchia.github.io/papers/ESEM_2024.pdf. Data on Zenodo.

Empirical follow-up to the authors' position paper (Verdecchia et al., IST 2023). It grew out of an ISERN 2023 session.

## TLDR
- **Question:** is the threats-to-validity (TTV) section a ritual ("hypocritical") or real analysis? The authors look at what the *best* papers do.
- **Sample:** all 91 ICSE papers with an ACM SIGSOFT Distinguished Paper Award from 2014–2023. Award winners were chosen to represent perceived top quality, not average practice. All four authors calibrated on 3 papers, then each coded about a quarter. The analysis is descriptive only, comparing 2014–18 with 2019–23.
- **What was coded:** study types, then seven questions: depth of reflection, checklist used, categories used, whether the categories fit the study type, proactive TTV analysis, limitations, and trade-offs.
- **Study types:** 60% of the papers are multi-method; the most common combination is design study + lab experiment (37%).
- **Depth:** 22% in depth, 56% shallow, 22% no reflection at all.
- **Guidance:** only **2 of 91** cite a checklist or guideline for their threat categories.
- **Categories:** internal (37%) and external (32%) dominate, then construct (22%); reliability and conclusion validity are rare. Qualitative trustworthiness criteria (credibility, transferability, etc.) appear in 7 papers. Internal and external are almost always used together, as a stock pair.
- **Fit:** only **32%** use categories that fit their study type, falling from 40% to 26% between the two periods. Papers with in-depth reflection fit far better (70% vs 29%).
- **Afterthought, not design:** 67% have a dedicated TTV section, but only **9%** discuss validity when describing the research design. **62%** mention no mitigation at all.
- **Limitations:** only 14% have a dedicated limitations section.
- **Trade-offs:** only **2 of 91** discuss trade-offs between threats.
- **Twelve "items to consider" (Table 2):**
  - *Design:* decide which validity types matter most for your goal and focus there (C1); reason about trade-offs between threats (C2); remember that every method brings its own threats (C3); use categories that fit the study type (C4); find a suitable checklist (C5).
  - *Implementation:* track the choices that affect validity (C6); reuse known mitigations from your sub-field (C7).
  - *Reporting:* analyse in depth, covering priorities, mitigations, rationale and what remains unmitigated (C8); write for the *users* of the research, not for the reviewers (C9).
  - *Reviewing:* judge TTV against the paper's claims, not by whether a section exists (C10); do not punish honesty about threats (C11).
  - *Reading:* interpret and cite results in light of their validity (C12).
- **Own threats:** "best paper" is ill-defined, the sample is one venue only, and the items are proposals that still need community validation.

## Teaching hooks
- The punchline: even award-winning ICSE papers treat validity as an *enforced afterthought* (the abstract's phrase).
- Personal link: the related work starts with Feldt & Magazinius (ESEM 2010, 43 papers from ESEM 2009). Ask: *what has changed in 15 years?* Apparently not much.
- C10 and C11 connect directly to Tuesday's reviewing seminar. A reviewer who punishes candour trains authors to write boilerplate.
- C2 and the 2-of-91 trade-off finding lead straight into Robillard et al. (TOSEM 2024).
- Exercise: use C1 + C8 on your own study. Which validity type matters most for *your* main claim, and what is still unmitigated?
