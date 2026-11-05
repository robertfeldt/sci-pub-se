# Replications, Revisions, and Reanalyses: Managing Empirical Evidence in Software Engineering

Frattini J, Fischbach J, Fucci D, Unterkalmsteiner M, Mendez D, Feldt R, Torkar R. *Frontiers in Computer Science* 8:1937190, 2026 (published 22 Sep 2026; open access, CC BY). https://doi.org/10.3389/fcomp.2026.1937190. Earlier version: arXiv:2412.12634 (Dec 2024).

## TLDR
- **Problem:** research synthesis in SE is rare and mostly narrative. Meta-analysis works reliably only for near-exact replications, and it cannot handle contradictory results or mediators and moderators. As a result, the *variance theories* SE produces (how much X affects Y) have limited validity.
- **Approach:** method engineering. The authors assemble a synthesis framework from proven method fragments, one per validity dimension. Construct validity is explicitly left out, since no reliable fragment exists for it.
- **Evidence = (hypothesis, data, method).** The hypothesis is typically drawn as a causal DAG. New evidence relates to old evidence in one of three ways, each changing *one* element:
  - **Replication:** new data, same hypothesis and method. Improves **external validity**; assessed by whether the conclusions agree (meta-analysis, overlapping intervals). A disagreeing replication signals a *causal leak* (a missing variable).
  - **Revision:** new hypothesis, e.g. adding a confounder or mediator. Improves **internal validity**; assessed by predictive power (AIC, LOO) for precision and by (conditional) independence tests for deconfounding. Predictive power alone can favour a confounded model.
  - **Reanalysis:** new analysis method, same hypothesis and data. Improves **conclusion validity**; assessed by whether the new method violates fewer statistical assumptions.
- **Evidence evolution graph:** studies form a graph. The field's **frontier** is the best-supported hypothesis paired with the most suitable method, and revisions that don't improve on their predecessor are "dead ends".
- **Demonstration 1, test coverage → test-suite effectiveness (1993–2020):** a sequence of replications and revisions over whether test-suite size confounds the effect. Some studies used the wrong criterion (R²) to decide on deconfounding.
- **Demonstration 2, passive voice in requirements → domain-model completeness:** an original student experiment reported a strong effect. A Bayesian reanalysis that was really a *revision mixed with a reanalysis* changed the picture. Separating the changes showed that participant skill (a random effect) explained much of the variance (conditional R² 0.56 vs marginal 0.18). The final estimate is 39% more missing associations, 47% equal, 14% fewer.
- **Recommendations:**
  - Frame each new study explicitly as a replication, revision or reanalysis, and change one thing at a time.
  - Record the variables future studies must control for.
  - Use the evidence graph when designing a study (what to measure, which analysis to use).
  - Let systematic reviews map the evolution of evidence, not just pool effect sizes.
- **Limitations:** quantitative evidence only (qualitative evidence can trigger revisions but is not synthesised); construct validity and quality appraisal are not covered; demonstrated retrospectively on two fields.

## Teaching hooks
- It gives the "validity types" a constructive role. Instead of listing threats, ask which type of study would improve which validity of the *existing* evidence.
  - external → replicate;
  - internal → revise the causal model;
  - conclusion → reanalyse.
- Links:
  - Cassee & Feldt's multiverse is a systematic way to probe the *reanalysis* dimension.
  - Lago et al. (C1, C7) and Robillard et al. (trade-offs) are the single-study view; this paper is the across-studies view.
  - Monday's evidence block: GRADE/CERQual rate certainty across studies, while this paper says how evidence should *evolve*.
- For PhD students: "what kind of contribution is my next study?" A well-framed replication or revision is a legitimate, publishable contribution.
- Demonstration 2 is an honest example of the group revisiting its own earlier analysis.
