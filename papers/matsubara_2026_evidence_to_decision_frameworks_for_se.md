# Matsubara & Conte (2026), "Bridging the Gap: Adapting Evidence to Decision Frameworks to support the link between Software Engineering academia and industry"

**Links:** https://arxiv.org/abs/2602.08015

5-page vision paper, ICSE Future of Software Engineering (FoSE) 2026, arXiv 2602.08015.

- **Problem:** 20+ years of evidence-based SE and many systematic reviews, yet review results don't reach practitioners: "something is missing". SE took the *evidence-grading* half of GRADE but not the *recommendation* half.
- **Proposal:** adapt health care's **Evidence-to-Decision (EtD) frameworks**. A systematic review synthesises evidence and grades certainty; then an **expert panel** uses the review plus other explicit criteria to make a structured recommendation.
- **Three EtD steps:**
  1. **Formulate the question:** population, intervention, comparison, outcomes (PICO), plus setting, perspective (individual vs organisation), subgroups, and **panel conflicts of interest**.
  2. **Assess criteria:** priority of the problem; size of desirable and undesirable effects; certainty of evidence; balance of effects; resource requirements and certainty about costs; cost-effectiveness; **acceptability** to stakeholders; feasibility (criteria depend on the type of decision).
  3. **Conclude:** direction (for/against) and strength: *strong* (almost everyone would choose it) vs *discretionary/conditional* (depends on values, trade-offs, context), plus implementation and monitoring advice and research gaps.
- **Worked SE example (partly fictitious):** "Should pair programming be adopted?", inspired by Hannay et al.'s meta-analysis. Population: developers; comparison: solo; outcomes: duration, effort, quality; perspective: organisation/team; subgroup: inexperienced developers; one panel member declares a conflict (sells training). Result: a **discretionary** recommendation (higher effort may be unacceptable for some organisations), advice to have a productivity measurement in place, and research gaps.
- **Challenges for SE:**
  - *Who issues recommendations?* SE has no WHO or medical societies; maybe ACM SIGSOFT / IEEE TCSE panels or special issues.
  - *Platforms:* practitioners prefer Q&A sites (StackExchange) to static Evidence Briefings.
  - *Types of decisions:* individual developer vs team vs organisation (project vs senior managers).
  - *Outcomes:* aggregate evidence around agreed outcomes of interest (maintainability vs user experience, etc.).
  - *"Practice questions"* as the SE counterpart of clinical questions, distinct from research questions; much SE research answers questions industry doesn't ask.
- **Takeaway:** effectiveness evidence alone is insufficient: an intervention may be too costly or unacceptable to stakeholders. EtD makes all the decision-relevant information explicit and shows where evidence is missing.
- **Teaching hooks:** pairs with Core GRADE paper 7 and with Cartwright & Hardie ("will it work here?"). Question for the room: who could legitimately issue SE practice guidelines?
