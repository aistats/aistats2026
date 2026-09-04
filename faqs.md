---
title: FAQs
layout: default
---

## Frequently Asked Questions on AISTATS 2026 Submissions & Accepted Papers

1.  **I missed the abstract submission deadline. Can I still submit a full paper?**
    No. You must submit the abstract in time for the deadline on Thursday, September 25, 2025 (AoE).

2.  **While submitting a paper, do we need to nominate one of the authors as a reviewer?**
    We ask authors to also serve as reviewers in order to ensure that all submissions can receive a sufficient number of reviews whilst ensuring an acceptable load for each reviewer. Due to the recent increase in submissions, we expect we will need a significantly larger number of reviewers than in previous years. Your nominations are important in order to maintain the quality of the conference. There will be a section in the paper submission form to nominate any of the authors to be reviewers.

3.  **We want to submit a version of the work to arXiv. Is it allowed?**
    Yes, submission to arXiv is allowed. However, keep anonymity in the AISTATS submission. Do not cite the arXiv paper, for example.

4.  **Can we advertise the preprint of my submission on social media?**
    We strongly discourage advertising the preprint on social media or in the press while under submission to AISTATS. Under no circumstances should your work be explicitly identified as AISTATS submission at any time during the review period, i.e., from the time you submit the abstract to the communication of the accept/reject decisions.

5.  **Can the author list be changed?**
    The author list is **<u>final at the abstract submission deadline</u>** (Thursday, September 25, 2025, AoE). After the abstract deadline, any changes to the author list are **impossible**. This is to avoid conflicts of interest with reviewers during the matching, which begins right after the abstract submission deadline. Only once the paper is accepted, you may change the order of authors, but no new authors may be added. (See also item 21.)

6.  **Can I withdraw my submission?**
    Yes. You can withdraw your submission at any point in the reviewing process. For statistical purposes, we will count a submission as “rejected” if it is withdrawn after reviews have been made available to authors.

7.  **Can we revise the abstract after the abstract deadline?**
    You can revise your abstract before the full paper deadline, but the changes must be minor (e.g., fixing typos or clarify/correct wording). If the contents or length of the abstract is significantly altered, the submission may be desk-rejected.

8.  **If our paper is a resubmission from a previous conference, do I have to indicate so in the submission form?**
    Yes, authors must specify whether the paper is a resubmission and, if so, they must summarize the main criticisms raised by the previous reviewers and how these have been addressed. This information will be visible to Area Chairs only, but not to reviewers.

9.  **Can we submit code/dataset with our submission?**
    Yes, and authors are encouraged to do so, as long as anonymity is preserved. For example, you may include your code as part of the supplementary material or through an anonymized link. Please note that papers that promise to release code or dataset (either at submission time or during the rebuttal phase) will be automatically rejected if the authors fail to make the code/dataset public by the camera-ready deadline.

10. **Does the paper need to discuss the method assumptions and limitations?**
    It is not compulsory, but authors are nonetheless encouraged to discuss these points, as they will be positively considered during the review phase.

11. **Does the paper need to discuss the societal impact?**
    It is not mandatory, but authors are encouraged to discuss the societal implications of their research.

12. **Is there a reproducibility checklist that my paper needs to comply with?**
    This year we ask the authors to include a reproducibility checklist in the main paper after references. The checklist does not count towards the 8 page main limit for the submission (or 9 page limit for camera ready). The submission template includes the checklist details.

13. **Will my submission be desk-rejected if not including the reproducibility checklist?**
    No, but we still strongly suggest the authors include the checklist in submission. If not included, the authors will be asked to submit the checklist during the author feedback period. The checklist is required for the camera ready version of an accepted paper.

14. **Will the questions about industry/academic paper or hardware usage be visible to reviewers or affect the paper decision?**
    No, this information will not be visible to reviewers or ACs and will not be taken into account in the paper decisions. It will only be used for statistical purposes.

15. **Can we revise our submission PDF or post updated figures during the rebuttal / author-reviewer discussion phase?**
    The author-reviewer discussion phase is text-only. No revision to the manuscript is allowed until acceptance. Authors are NOT allowed to include links during the discussion phase. Posting external links can be grounds for violating the double-blind requirement and can lead to the immediate rejection of your paper.
    Note that OpenReview markdown does not support images or inline-html; see the [specification](https://spec.commonmark.org/0.29/). (La)TeX-type math is supported through MathJax inside markdown, see the [documentation](https://docs.openreview.net/how-to-guides/submissions-comments-reviews-and-decisions/how-to-add-formulas-or-use-mathematical-notation).

16. **How can we obtain the citations (references) of our paper in the (Author, Year) format?** One option to achieve that goal is to use the latex package `natbib`. For that, you may uncomment lines 28-30 and 33 at the beginning of your main TEX file (sample_paper.tex in the [AISTATS 2026 Paper Pack](https://aistats.org/aistats2026/AISTATS2026PaperPack.zip)). In other words, you can use the following:
    `% If you use natbib package, activate the following three lines:`
    `\usepackage[round]{natbib}`
    `\renewcommand{\bibname}{References}`
    `\renewcommand{\bibsection}{\subsubsection*{\bibname}}`

    `% If you use BibTeX in apalike style, activate the following line:`
    `\bibliographystyle{apalike}`

    `[...] [YOUR DOCUMENT HERE]`

    `\bibliography{your_bib_file} `

    Note that, when using `natbib`, you can add or remove the parentheses as follows:
    `\cite{foo2021} % produces Foo et al. (2021)`
    `\citep{foo2021} % produces (Foo et al., 2021)`

17. **Due to visa issues (or travel emergencies), it is possible that none of the authors can attend the conference. Can we present virtually or pre-record our talk if our paper is accepted? **As outlined in the [Call for Papers](https://virtual.aistats.org/Conferences/2026/CallForPapers), at least one author of each accepted paper must attend the conference and present the work. Exceptions may be considered in cases such as travel emergencies or visa issues. <u>These are evaluated on a case-by-case basis and usually require proof that a genuine attempt was made to attend.</u>

    *\*\*\*If no authors from an accepted paper can attend, please fill out **[this Google form](https://forms.gle/QKRmsqGFVKF94dpa6)** and select "None of the authors can make it to the conference at all" for the last question. Requests will be reviewed case-by-case. \[Updated March 24, 2026: At this point, we are only accepting requests in very exceptional circumstances, such as visa refusals and travel/medical emergencies. If you are in such a situation, fill out the form and email the PCs as soon as possible so that the program schedule can be finalized.\]*

18. **In an exceptional case, will there be a remote presentation option? **Unfortunately, the conference is designed to be in-person only. There will be no remote presentation options for posters and talks.

19. **Is a conference registration required for an accepted paper, even if I cannot attend in person? **If you were granted an exception (see question 17), then you do not need to register.

20. **Can I change the title of my paper in the camera-ready phase? **You can make minor modifications to the title. Also note the capitalization of the title (title case).

21. **How do I change the author order for an accepted paper? **If you want to change author order during the camera-ready phase, you can do that in OpenReview in the camera-ready form. Authors cannot be removed/added in the camera-ready phase.

22. **When do the accepted paper PDFs go public? **The paper PDFs will be made public after the camera-ready phase, before the conference. The exact date depends on any additional format checks that have to be done.

23. **How to apply for a Travel Grant / Financial Support? **We will provide updates as soon as we have information available.
