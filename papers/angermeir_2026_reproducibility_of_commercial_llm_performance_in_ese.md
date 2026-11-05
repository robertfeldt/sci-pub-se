# Reflections on the Reproducibility of Commercial LLM Performance in Empirical Software Engineering Studies

Angermeir F, Amougou M, Kreitz M, Bauer A, Linhuber M, Fucci D, Moyón C F, Mendez D, Gorschek T. *ICSE '26* (48th International Conference on Software Engineering), Rio de Janeiro, 2026. https://doi.org/10.1145/3744916.3773207. Open access (CC BY 4.0). Preprint: https://arxiv.org/abs/2510.25506

## TLDR
- **Question:** are LLM-centric empirical SE studies reproducible, what gets in the way, and do ACM artifact badges reflect reproducibility?
- **Sample:** 78 of the ~425 ICSE 2024 papers ran LLM experiments, plus 7 badged ASE 2024 papers, giving 85 papers (69 using OpenAI models). 18 provided artefacts and used OpenAI models; only **5** were complete and executable enough to try.
- **Procedure:** five researchers reran each study in containers, up to 30 runs or $500. Results were compared with Bayesian bootstrap intervals. The original authors were not contacted.
- **Result: 0 of 5 fully reproduced.** 2 partially reproduced and 3 did not reproduce.
- **What blocked reproduction:**
  - missing or incomplete artefacts (35 of the 85 papers had no code or data);
  - unpinned dependency versions;
  - plain code problems (hard-coded paths, unassigned variables);
  - **deprecated models** (e.g. text-davinci-003, code-davinci-002), the one LLM-specific factor.
- **Reporting gaps across the 85 papers:** 8 do not even name the model; only 29 report temperature; 22 describe how context windows were handled; 50 report prompts.
- **Badges:** of 16 papers with the ACM "Reusable" badge, **8 failed ACM's own requirements** (incomplete, non-functional or under-documented). Badges are not a reliable indicator of reproducibility.
- **Recommendations:**
  - *Authors:* follow LLM reporting guidelines (Baltes et al., TRIPOD-LLM); report the model version and parameters, context-window handling and prompts; share complete, versioned artefacts.
  - *Venues and artifact committees:* mandatory artefact disclosure (incl. a software bill of materials); stricter, longer-lived evaluation criteria.
  - *Funders:* the same rigour as for other research; long-term artefact accessibility.

## Teaching hooks
- The empirical sequel to Sallou et al. (2024): the threats they warned about did materialise in ICSE/ASE 2024 papers.
- For S5b (trust): reproducibility fails even without any fraud. And the community's trust signal (badges) does not measure what it claims to.
- Plenary question: should ESEM/EMSE require executable artefacts for LLM studies? Who pays the cost of that (industry data, API costs, models that disappear)?
