# An Evidence Profile for Software Engineering Research and Practice

Wohlin C. Book chapter in *Perspectives on the Future of Software Engineering* (Springer, 2013); this copy is an author preprint.

## TLDR
- **Problem:** evidence-based SE needs a way to synthesise and *value* evidence from heterogeneous studies (experiments, case studies, surveys), where meta-analysis is often impossible. The best evidence in SE is context-dependent, unlike medicine's randomised-trial-on-top hierarchy. Industry also asks for evidence relevant to its own context (example: a telecom manager wanted evidence on moving development between sites, but the evidence found was from other domains and judged of limited value).
- **Analogy with criminal law:** decisions about SE methods and tools could be made the way law is practised, but with a lower bar than "beyond reasonable doubt": the evidence should be reasonable and acting on it cost-efficient. Legal sources, strong to weak: physical evidence, eyewitnesses, expert witnesses, circumstantial evidence; then non-evidence: hearsay, self-statements, suspicion (≈ "gut feeling", still useful as a starting point to look for real evidence).
- **Aspects that modify how a piece of evidence is valued:** quality (reliability; corroboration by triangulation), relevance to the situation, *aging* (technology change can make evidence obsolete), vested interest, and strength.
- **Five types of evidence (the evidence profile):**
  1. *Strong evidence:* e.g. well-documented controlled experiment with industrial participants, or cross-company multi-case study; by researchers independent of the inventor; peer reviewed.
  2. *Evidence:* e.g. experiment with non-representative subjects, or series of case studies within one company; peer reviewed; independent researchers.
  3. *Circumstantial evidence:* e.g. experiment by someone with a vested interest, single case study, cross-company survey; peer reviewed.
  4. *Third-party claim:* experience reports, lessons learned, single-company surveys, published anywhere, by someone without a vested interest.
  5. *First- or second-party claim:* anything published by the inventor or others with a vested interest (e.g. a tool vendor).
- **Evidence can be positive or negative**, so the profile has 11 cells: five positive types, five negative types, and one for inconclusive results. Counting studies per cell gives a bar chart, the *evidence profile* for an object of study in a given context.
- **Guidelines, not definitions:** each placement must be motivated and the underlying studies made available, so the profile can be checked and challenged. Placements can change with context (general research vs a specific company's needs).
- **Illustration: perspective-based reading (PBR) vs checklist-based reading,** using the 22 studies from Ciolkowski's meta-analysis:
  - 3 studies dropped (no comparison), 12 inconclusive.
  - 4 significant pro-PBR industry studies placed only in "evidence" (not "strong") because all involve authors of the original PBR paper (vested interest); 1 student study as a first/second-party claim; 2 significant pro-checklist studies as negative "evidence".
  - Overall: quite inconclusive, slightly favouring PBR, and *all* significant results involve authors of the original paper.
  - Industry scenario (telecom company inspecting requirements, design, code and tests): no evidence at all for code and test documents and very little for design, so no switch to PBR there; maybe an experiment for requirements.
- **Takeaway:** a light-weight, transparent, context-sensitive way to package evidence for both researchers (find gaps) and practitioners (make decisions), intended for any type of empirical study. Further evaluation, including in systematic reviews, is left as future work.
