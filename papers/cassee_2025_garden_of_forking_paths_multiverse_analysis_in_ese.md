# Exploring the Garden of Forking Paths in Empirical Software Engineering Research: A Multiverse Analysis

Cassee N, Feldt R. arXiv:2512.08910 (v1 Dec 2025, revised 2026), submitted to ACM TOSEM. https://arxiv.org/abs/2512.08910

## TLDR
- **Question:** how sensitive are the conclusions of an empirical SE study to defensible analysis decisions? The "garden of forking paths" is Gelman & Loken's term for this freedom.
- **Case:** a reanalysis of Cassee, Vasilescu & Serebrenik, "The Silent Helper: The Impact of Continuous Integration on Code Reviews" (SANER 2020). It uses Regression Discontinuity in Time (RDiT) on code reviews from 685 GitHub projects that adopted Travis CI, with four hypotheses: CI affects general comments (H1), review comments (H2), changes made because of reviews (H3), and commits during review (H4). The original finding was less review communication after CI and no effect on changes.
- **Decisions varied:**
  - *Time modelling:* number of periods, period length (7/15/30/45 days), the exclusion window around adoption;
  - *Aggregation:* scaling (none/ln/log10), mean vs median, rounding precision;
  - *Model:* collinearity (VIF) threshold, REML fitting.
- **Result:** 3,072 pipelines and 12,288 models. **Only 6 universes (0.2%) reproduce all the published findings**. Many give unconfirmed or even *opposite* claims, and some models fail to fit. The communication results (H1, H2) are more stable than the change results (H3, H4).
- **The most influential decision is period length,** which changes the outcome in most universes, and it is usually chosen by default or by convention. Even a *hidden* decision (rounding precision set by the programming environment's default) changes the outcome in about 2% of universes.
- **Justification Ladder of Analytical Choices (JLAC),** from weakest to strongest:
  1. *Implicit:* made without noticing, e.g. a software default;
  2. *Conventional:* "it's what others do";
  3. *Heuristic:* a general rule of thumb not tied to the domain;
  4. *Empirical:* justified by properties of the data;
  5. *Causal:* justified by a causal model or theory of the domain.
- **In RDiT studies,** period length is almost always level 1 or 2. The common 15-day exclusion window became a convention (level 2) after one study's anecdotal observation (level 3).
- **Recommendations:**
  - Make decision points explicit and justify each one as high on the ladder as possible.
  - Use simulated data with known effects to check that the analysis can recover them.
  - Preregister; triangulate.
  - Run multiverse or sensitivity analyses and report them; call data-driven analyses *exploratory rather than confirmatory*.
  - The community should develop domain guidance for decisions such as period length.
  - Multiverse analysis works as a "smoke test" for robustness.
- **Limitations:** a single case; data selection was not varied; some branches may drift from the original constructs; it does not address the primary study's causal and confounding issues.

## Teaching hooks
- The strongest empirical complement to Robillard et al. (2024): undocumented design choices are not just poor reporting; they can flip the result.
- One of the authors reanalysed his own earlier paper, which makes it a good example of honesty about one's own work (cf. Lago et al.'s C11: "do not punish honesty").
- Exercise (S4): classify three analysis or design decisions in your own study on the JLAC ladder. Which are implicit or conventional?
- For S5b (trust): fragile results do not need fraud. Analytic flexibility plus well-meaning choices is enough, and preregistration and sensitivity analyses are defences against both.
