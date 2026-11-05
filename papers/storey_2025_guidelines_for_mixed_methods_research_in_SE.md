# Guiding principles for mixed methods research in software engineering

Storey M-A, Hoda R, Milani AMP, Baldassarre MT. *Empirical Software Engineering* 30:138, 2025 (accepted 17 Feb 2025, published 9 Jul 2025; open access). https://doi.org/10.1007/s10664-025-10629-x. Preprint: arXiv:2404.06011 (earlier versions were titled "Guidelines for Using Mixed and Multi Methods Research in SE").

## TLDR
- **Problem:** SE researchers mix methods all the time but rarely say so, or justify the design. A look at a year of EMSE and IST issues found many mixed-methods papers that neither name nor justify their design. Researchers without social-science training lack guidance.
- **Definition:** mixed methods research (MMR) uses multiple methods to collect, analyse and *integrate* both qualitative (quaL) and quantitative (quaN) data to address a research problem and produce novel insights. *Multi-method* research (quaN+quaN or quaL+quaL) is different, but the same principles apply.
- **Four guiding principles:**
  1. **Methodological rationale:** say *why* this mix. Reasons: complementarity, expansion, development (one method builds the instrument for another), triangulation (across McGrath's generalisability, realism, precision and control), credibility, explanation of surprising results, design flexibility.
  2. **Novel integrated insights:** the mix must produce *meta-inferences* that no single method gives, and the report must show how methods and data were integrated.
  3. **Procedural rigour:** each method meets its own standards, *and* the mixing is justified and integrated.
  4. **Ethical research:** why the research is done; re-identification risks when data sources are combined; respect for the people studied.
- **Design properties:**
  - an MMR research question (what the *combination* will tell you);
  - planned vs emergent (e.g. a second method added after surprising results);
  - inductive or deductive dominance (not the same as quaL vs quaN);
  - timing: sequential or parallel.
- **Four types of integration:** sequential (one method's findings shape the next), results-based (compare after both analyses), data-based (both data types per case, analysed together), transformation-based (convert quaL to quaN or the reverse). Joint displays help.
- **Core designs, each with a recent EMSE/IST example:**
  - **Exploratory sequential:** quaL → quaN, e.g. 20 interviews, then a survey of 423, on psychological safety in agile teams.
  - **Explanatory sequential:** quaN → quaL, e.g. mining defects, then interviews to explain them.
  - **Convergent parallel:** both at once, looking for convergence *and* divergence.
  - **Embedded:** a secondary method nested in a primary one, e.g. a survey inside an experiment.
- **Four fictional researcher scenarios** illustrate the designs and their trade-offs: Ali (security tool; exploratory, planned), Sam (a PhD student mining GenAI code-review telemetry who adds interviews; explanatory, emergent), Vicki (onboarding via Slack + commit mining; convergent), Zara (test-generation experiment + embedded survey).
- **Antipatterns:**
  - *Presentation (fixable in the write-up):*
    - **uninvited guest**: a method first appears in the discussion;
    - **smoke and mirrors**: a token second strand sold as MMR;
    - **limitation shirker**: limitations of every method and of the integration are not discussed.
  - *Study design (hard to fix afterwards):*
    - **missing the mark**: a method doesn't serve the research question;
    - **selling your soul**: a method added only to please an anticipated reviewer;
    - **cargo cult research**: using methods the team lacks expertise in because they appear in well-cited papers;
    - **sample contamination**: unreported reuse of participants across strands;
    - **lost opportunity**: early findings don't inform later instruments;
    - **integration failure**: findings never really combined;
    - **questionable ethics**.
- **Call to action:**
  - Use MMR in a principled, ethical way to make SE research more human-focused ("they are real people").
  - Bring in collaborators with other expertise.
  - With AI tools tempting us to speed up research, ask "why", not just "why not", and protect deep qualitative work.

## Teaching hooks
- The constructive answer to Williams/Storey 2019 (SE rarely triangulates; reviewer pressure on generalisability). "Selling your soul" is that pressure turned into an antipattern.
- For S4 pairs: "Could your alternative method be a second *strand*? Which of the four designs would it be, and where would you integrate?"
- Many participants combine interviews and surveys. Which antipatterns apply? Uninvited guest and integration failure are the most common in submissions.
- Links: Wohlin & Runeson 2021 (choice of methodology), the ABC framework (triangulation across quadrants), Petersen & Gencel (worldviews; MMR as the "third paradigm"), ACM SIGSOFT Empirical Standards (MixedMethods standard, available in `offline/empirical_standards_repo/docs/standards/MixedMethods.md`).
- Sam's scenario (a PhD student studying a GenAI tool) is close to several participants' own projects.
