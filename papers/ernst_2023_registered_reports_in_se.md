# Registered reports in software engineering

Ernst NA, Baldassarre MT. *Empirical Software Engineering* 28:55, 2023 (editorial; published online 11 March 2023). https://doi.org/10.1007/s10664-022-10277-5 (summary only; not open access).

## TLDR
- **What a registered report (RR) is:** the study protocol (research questions, hypotheses, variables, methods, analysis plan) is peer-reviewed *before* the study is run. If it is approved ("in-principle acceptance"), the results are published as long as the protocol is followed, even if the hypothesis is not supported.
- **Why:** publishing on the basis of significant results invites questionable research practices: HARKing, forking paths, post-hoc stories presented as confirmatory evidence, and the file-drawer effect that skews systematic reviews. A well-run study that finds no evidence of an effect (e.g. of TDD on code quality) is still useful to practitioners. RRs move the focus to the importance of the question and the soundness of the method.
- **The SE model, conference + journal:**
  - **Stage 1:** a 5–6 page protocol is reviewed in an RR track at MSR (first, in 2020), ICSME or ESEM, for the importance of the questions and whether the methods can answer them. Pilot data is allowed. The accepted protocol is usually posted as a preprint.
  - **Stage 2:** the study is run, presented at the conference, and the full paper is reviewed at EMSE, mainly for how closely it follows the protocol. In practice the first Stage 2 decision has usually been minor revisions.
  - Review criteria are in the ACM SIGSOFT Empirical Standards (Registered Reports supplement). TOSEM runs a journal-only "Registered Papers" variant.
- **Early numbers (to late 2022):** across MSR 2020–22, ICSME 2020–21 and ESEM 2021–22, 6 papers had been published in EMSE after Stage 2 and 16 more were under Stage 2 review (Table 1).
- **Lessons:**
  - A survey after MSR 2020 (25 responses): every respondent would submit to an RR track again. 4 pages felt too short. 18 were comfortable with Stage 1 leading to an EMSE paper, 6 were not. Reviewers valued focusing on method without results; one felt uncomfortable carrying that responsibility so early.
  - The workload for editors and chairs is high: educating reviewers about Stage 1 vs Stage 2 criteria, and "editorial tennis" between venues and systems (EasyChair, HotCRP, Editorial Manager).
  - Typical deviations: fewer participants than planned, a different participant pool, or redefined constructs (e.g. productivity).
  - Policies were needed on authorship changes and conflicts of interest. Stage 1 reviewers and their students cannot become authors.
  - Feared problems did not materialise: neither scooping of published protocols nor people using Stage 1 as a substitute for supervisor feedback.
- **Benefits:** early feedback on study design (a kind of shepherding, even for rejected submissions), protection against researcher bias through pre-registration, and in-principle acceptance as an incentive.
- **Limits:** RRs fit confirmatory research best. Qualitative and exploratory studies, and data-mining studies without a priori hypotheses, were hard to review as Stage 1 protocols. MSR, followed by ICSME and ESEM, introduced "continuity acceptance" (accepted at Stage 1 but without in-principle acceptance) for these. Open questions: what registration means for qualitative and non-positivist research, and whether Stage 1 review is rigorous enough.

## Teaching hooks
- A concrete SE answer to Munafò et al.'s call for Registered Reports, and one defence against fabricated or p-hacked results discussed in Seminar 5.
- Exercise: could your current study be registered? If not, is it exploratory, and is that stated in the paper?
- Note the editorial's framing: exploratory work that does not fit registration "should not be seen as 'less than'" confirmatory work.
