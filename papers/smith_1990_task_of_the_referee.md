# The Task of the Referee

Alan Jay Smith. *IEEE Computer* 23(4):65–71, April 1990. https://doi.org/10.1109/2.55470. Free version: UC Berkeley technical report (May 1989), https://www2.eecs.berkeley.edu/Pubs/TechRpts/1989/6154.html. Summary made from the technical report.

## TLDR
- **Goal:** guidelines for referees in applied computer science (systems, architecture, performance) on how to evaluate a paper and write a report. By implication it also tells authors how to write a paper. Refereeing is "a public service" and a professional obligation, usually learnt only by experience.
- **Two parts of a report:** (a) a recommendation for or against publication *in this specific venue*, with enough discussion to justify it; (b) a list of necessary and recommended changes. A reject still comes with suggestions that could get the paper published elsewhere.
- **Walk the fine line:** being too permissive encourages bad research and misleads readers, authors and hiring committees. Being too critical blocks or delays good work and damages careers. Take particular care not to reject significant work that goes against prevailing wisdom. A referee who always says yes, or always says no, is not helpful.
- **Structure of a good report:** summarise the point of the paper in 1–5 sentences (which also checks that *you* understood it); evaluate the goal (validity and significance); evaluate the quality of the work; give an overall recommendation and state how strongly you hold it. Criticise the paper, not the author ("fool", "idiot" and "trash" are out). Be on time: "Imagine if it were your paper!"
- **Questions for evaluating research:**
  - What is the author trying to do? Is it clear, to you and to the author? Is it right for this venue?
  - Is the goal significant? Is the problem real, or "an elegant study of the flight characteristics of pigs" (the Walrus and the Carpenter)?
  - Is it new? Is the author aware of old and recent related work, and are the differences specific?
  - Is the method valid? What are the assumptions, how realistic are they, and how sensitive are the results to them?
  - Is the execution correct? Confidence intervals for stochastic simulations; did the author do what is claimed?
  - Are the right conclusions drawn, with a discussion of *why* the results came out as they did?
  - Is the presentation satisfactory? An incomprehensible paper is not publishable.
  - **What did you learn?** If the intended reader learns nothing, the paper is not publishable.
- **Seven quality categories:** (1) major results (<1% of papers); (2) good, solid, a definite contribution (<10%); (3) minor but positive (perhaps 10–30% of submissions); (4) elegant and correct but useless; (5) neither elegant nor useful but not wrong; (6) wrong and misleading; (7) too badly written to evaluate. Normalise to the standards of the field, not your own. Then compare with the *average* paper in the target venue, not its best or worst.
- **Revisions:** check that the revision is satisfactory, but be cautious about raising "new" problems that were already in the first version. Don't harass authors with revision after revision.
- **Surveys, tutorials and proposals** need different criteria. For proposals, Smith argues the investigator's track record should count for as much as 75%, while warning against discriminating against newcomers without a record.
- **Other issues:**
  - Simultaneous submission without telling the editors is unethical and grounds for rejection.
  - Republication needs disclosure and a higher bar.
  - If a paper you rejected elsewhere comes back unchanged, return your old review with a blunt note.
  - Point out plagiarism and missing acknowledgements.
  - Return papers you cannot review promptly (4–8 weeks for journals) or are not qualified to review. But you may have been chosen deliberately for an outside view: "Someone has to say that the emperor has no clothes."
  - Author reputation should matter only a little, and only for resolving ambiguities. Never assume an unknown author is a bad one.
  - Don't use or distribute submitted material. Declare conflicts of interest, both negative (feuds, competitors) and positive (friends, students, advisors).
- **Editors and PCs:** an editor does not count votes; the reasons in the reports weigh as much as the recommendations. Conference PCs typically decide by majority vote, and papers get less individual attention than at journals.
- **For authors:** ask how your paper will fare against these criteria, and pick the right venue. A good report is "immensely valuable, even if it tears your paper apart". Individual reports are often wrong, but a *set* of negative reports is "a 90% accurate indicator" that the paper has a problem.

## Teaching hooks
- More than 35 years old, yet most of it still applies. What is new now: submission volume (the CHI 2027 desk rejects), LLM-assisted reviewing, and formal review obligations at ICSE, FSE and ICLR.
- The 7 categories and "compare with the average paper in the venue" are a good calibration exercise: where does your own paper fall?
- Smith's tacit "good referee" virtues vs the explicit ACM SIGSOFT Empirical Standards.
