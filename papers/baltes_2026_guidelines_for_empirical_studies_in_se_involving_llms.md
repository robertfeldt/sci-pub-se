# Baltes et al. (2026), "Guidelines for Empirical Studies in Software Engineering involving Large Language Models"

**Links:** https://llm-guidelines.org/ (living guidelines; summary is of release 2026.09) · paper: https://arxiv.org/abs/2508.15503

EMSE (accepted manuscript; submitted 08/2025, final revision 06/2026). 22 authors (incl. Ralph, Prechelt, Wagner, Fucci, Martinez Montes). Living version at llm-guidelines.org.

- **Problem:** LLM-based SE studies are hard to reproduce, for three reasons:
  - non-determinism;
  - commercial models drift *behind the same version name*;
  - training data is undisclosed, even for "open" models.
- **Evidence for the problem:**
  - Angermeir et al.: of 85 LLM papers at ICSE/ASE 2024, 18 used OpenAI models and shared artifacts. Only 5 could be executed, and **none fully reproduced** their results.
  - Evertz et al.: every one of 72 papers had at least one LLM pitfall, and only 15.7% of the pitfalls were discussed.
- **Process:** started at an ISERN 2024 session, then a position paper, then the CHASE-AI 2024 workstream with bi-weekly meetings and ≥2 leads per section. Explicitly modelled on CONSORT and TRIPOD-LLM. Every author read and endorsed everything.
- **Taxonomy of 7 study types:**
  - *LLMs as research tools:* annotators, judges, synthesis, subjects (simulated participants).
  - *LLMs as SE tools:* studying usage, building new tools, benchmarking.
- **8 guidelines**, each split into MUST and SHOULD:
  1. Declare LLM usage and role.
  2. Report model version, configuration and customisations (fine-tuning, RAG, …).
  3. Report system and prompt design, beyond the model itself.
  4. Report session traces (interaction logs, runtime traces).
  5. Use suitable baselines, benchmarks and metrics (watch for data contamination).
  6. Include an **open LLM baseline** (open-weight at minimum; open-source ideal) and report inter-model agreement.
  7. **Human validation:** define the construct and the instrument. If LLMs *replace* humans (annotation, coding, simulated participants), justify it with model–human and inter-model agreement.
  8. Report limitations and mitigations (non-determinism, generalisation across models and over time, proprietary parts).
- **Extras:** an applicability matrix (guideline × study type) and a reporting checklist (Appendix C) for authors *and* reviewers.
- **Advantages acknowledged:** speed, cost and scale. One example: annotation took 2 days and $122 with GPT-4, versus weeks and $4,508 on MTurk. Higher consistency in some tasks.
- **Self-assessment:** the authors judge the guidelines against the SIGSOFT Empirical Standards quality dimensions (comprehensive, useful, …).

**Teaching hooks**
- A living example of how a community *creates* a standard (cf. CONSORT, Empirical Standards, GRADE). Ties to Monday's evidence-standards theme.
- Ask participants: which of the 8 would your last LLM paper fail? (Usually #2, #4 and #6.)
- Contrast with venue AI policies (ICLR 2027, ICSE/FSE 2027): those govern *authoring with* LLMs, while these guidelines govern *researching with* LLMs.
