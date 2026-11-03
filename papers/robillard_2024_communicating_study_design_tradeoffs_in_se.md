# Communicating Study Design Trade-offs in Software Engineering

Robillard MP, Arya DM, Ernst NA, Guo JLC, Lamothe M, Nassif M, Novielli N, Serebrenik A, Steinmacher I, Stol K-J. *ACM Transactions on Software Engineering and Methodology* 33(5), article 112, 10 pages, 2024. https://doi.org/10.1145/3649598. Author copy: https://cs.mcgill.ca/~martin/papers/2024-tosem-tradeoffs.pdf. Also presented as journal-first at RE 2025.

## TLDR
- **Problem:** threats-to-validity and limitations sections rarely explain *why* the design decisions were taken, or what they cost. Three weaknesses:
  - **Boilerplate:** generic statements such as "the study is limited to its context". Merely stating that sample size limits external validity is called a truism.
  - **Defensive writing:** authors downplay their choices to pre-empt reviewers, which hides the design space. Justifying a choice by citing an earlier paper that made the same choice assumes that decision was right and still applies.
  - **Opacity:** readers see the limitations but cannot judge whether the trade-off behind them was reasonable.
- **Proposal:** replace the list of threats with an account of the **design trade-offs**. Each decision is one option among alternatives; argue how its benefits outweigh the costs of those alternatives. Threats still appear, but as *implications* of decisions.
- **Five-part reporting guideline for each major trade-off** (recommended, not mandatory):
  1. **Decision point:** the decision and the value chosen (e.g. "number of companies: three").
  2. **Alternatives:** the options considered. Is the set closed? Are the options mutually exclusive?
  3. **Considerations:** costs and benefits of each option, and the constraints (budget, access, ethics). Back these with evidence where possible, e.g. pilots or sensitivity analyses.
  4. **Rationale:** why this option, given the considerations.
  5. **Implications:** consequences for the findings, including threats to validity, with evidence where possible.
- **Placement:** major trade-offs get their own section, one titled paragraph each (up to about a page for a big decision; use an appendix under page limits). Minor ones go next to the relevant method text. The structure is flexible: rich insight beats conformance to a template.
- **Three worked examples:**
  - *How many companies* in a turnover and knowledge-loss study (1 vs 2–3 vs many), trading triangulation against negotiation cost.
  - *Recruitment* for a study of GitHub bots: Prolific + students chosen over MTurk or direct outreach. Only 12% of volunteers passed screening, and about $42 per 100 volunteers went on unusable data, but screening increased confidence in validity.
  - *Self-reports vs telemetry* for developer productivity: self-reports chosen for trust and privacy, at the cost of fewer data points.
- **For reviewers:** judge trade-offs fairly and dispassionately, since no design is best in every respect. Calls for papers should encourage trade-off sections and account for the space they need.
- **Table 1:** ten works from other disciplines (policy, education, accounting, psychology, medicine, etc.) that already discuss design trade-offs. SE is a late adopter.

## Teaching hooks
- The positive alternative to the problem Lago et al. (ESEM 2024) diagnose: only 2 of 91 ICSE award papers discuss trade-offs.
- Links to the ABC framework (Stol, a co-author here): you cannot maximise generalisability, precision and realism at once, so *say what you gave up*.
- Exercise (Wed S4): rewrite one generic threat from your own paper as a five-part trade-off. Which alternative did you reject, and what did your choice cost?
- Reviewer angle (Tue S3): a candid trade-off section should earn credit, not ammunition.
