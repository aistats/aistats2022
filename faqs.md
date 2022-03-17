---
title: Submission FAQs
layout: default 
weight: 5
hide: true
---


## Frequently Asked Questions related to AISTATS 2022 submissions


1. **I missed the abstract submission deadline. Can I still submit a full paper?**
   No. You must submit the abstract in time for the deadline on October 8th.

2. **While submitting a paper, do we need to nominate one of the authors as a reviewer?**
Yes, at least one of the authors must be nominated to serve as a reviewer. You can nominate more than one and we encourage that. Nominations of authors who aren’t already a reviewer are preferred, but at least one of the authors of the paper must serve as a reviewer. Please do not nominate any author who is serving as an Area Chair for AISTATS. Due to the recent increase of submissions, we expect we will need a significantly larger number of reviewers than previous years. Kindly understand that your nominations will be important to keep the quality of the conference.

3. **We want to submit a version of the work to arXiv. Is it allowed?**
Yes, submission to arXiv is allowed. However, keep anonymity in the AISTATS submission. Do not cite the arXiv paper, for example.

4. **Can we advertise the preprint of my submission on social media?**
We strongly discourage advertising the preprint on social media or in the press while under submission to AISTATS 2022. Under no circumstances should your work be explicitly identified as AISTATS submission at any time during the review period, i.e., from the time you submit the abstract to the communication of the accept/reject decisions.

5. **Can the author list be changed?**
You can change the author list until the deadline of full paper submission (October 15th). After this point, only changes to the author order are allowed, but new authors won’t be added.

6. **Can I withdraw my submission?**
Yes. You can withdraw your submission at any point in the reviewing process. For statistical purposes, we will count a submission as “rejected” if it is withdrawn after reviews have been made available to authors.

7. **Can we revise the abstract after the abstract deadline?**
You can revise your abstract before the full paper deadline, but the changes must be minor (e.g., fixing typos or clarify/correct wording). If the contents or length of the abstract is significantly altered, the submission may be desk-rejected.


8. **I am an author as well as a reviewer/area chair, but I can only find my author (or reviewer) role in CMT. What should I do?**
On the CMT page, you will find a “Select Your Role” tab on the top right. If you click on the current role (e.g., Author), you will see a drop down menu showing your other roles, and you can pick the one you need.


9. **Can I use a different email for my CMT reviewer account and TPMS account?**
The easiest approach is to have the same email for your CMT account and the TPMS account. Alternatively, you may use the new “Linked Account” feature of CMT (see “Link to Account” in the dropdown list at the top right of the console), to link your Area Chair/Reviewer CMT account with another CMT account that uses the same email as your TPMS account. Regardless of the chosen path, it will be critical to have CMT and TPMS accounts with matched email addresses.


10. **If our paper is a resubmission from a previous conference, do I have to indicate so in the submission form?**
Yes, authors must specify whether the paper is a resubmission and, if so, they must summarize the main criticisms raised by the previous reviewers and how these have been addressed. This information will be visible to Area Chairs only, but not to reviewers.


11. **Can we submit code/dataset with our submission?**
Yes, and authors are encouraged to do so, as long as anonymity is preserved. For example, you may include your code as part of the supplementary material or through an anonymized link. Please note that papers that promise to release code or dataset (either at submission time or during the rebuttal phase) will be automatically rejected if the authors fail to make the code/dataset public by the camera-ready deadline.


12. **Does the paper need to discuss the method assumptions and limitations?**
It is not compulsory, but authors are nonetheless encouraged to discuss these points, as they will be positively considered during the review phase.


13. **Does the paper need to discuss the societal impact?**
It is not mandatory, but authors are encouraged to discuss the societal implications of their research.


14. **Is there a reproducibility checklist that my paper needs to comply with?**
Authors are encouraged to follow the suggested checklist provided at the end of this document.


15. **Will the questions about industry/academic paper or hardware usage be visible to reviewers or affect the paper decision?**
No, this information will not be visible to reviewers or ACs and will not be taken into account in the paper decisions. It will only be used for statistical purposes.

16. **How can we obtain the citations (references) of our paper in the (Author, Year) format?**
One option to achieve that goal is to use the latex package `natbib`. For that, you may uncomment lines 19-21 and 24 at the beginning of your main TEX file. In other words, you can use the following:

```
% If you use natbib package, activate the following three lines:
\usepackage[round]{natbib}
\renewcommand{\bibname}{References}
\renewcommand{\bibsection}{\subsubsection*{\bibname}}

% If you use BibTeX in apalike style, activate the following line:
\bibliographystyle{apalike}

[...] [YOUR DOCUMENT HERE]

\bibliography{your_bib_file}
```

Note that, when using `natbib`, you can add or remove the parentheses as follows: 

```
\cite{foo2021}   % produces Foo et al. (2021)
\citep{foo2021}  % produces (Foo et al., 2021)
```


## AISTATS 2022: Guidelines and Checklist


Below is a suggested guideline and checklist for paper submissions:


 1. **For all models and algorithms presented, check if you include:**
    1. A clear description of the mathematical setting, assumptions, algorithm, and/or model.
    2. An analysis of the properties and complexity (time, space, sample size) of any algorithm.
    3. (Optional) Anonymized source code, with specification of all dependencies, including external libraries.
 2. **For any theoretical claim, check if you include:**
    1. A statement of the result.
    2. A clear explanation of any assumptions.
    3. A complete proof of the claim.
 3. **For all figures and tables that present empirical results, check if you include:**
    1. A complete description of the data collection process, including sample size.
    2. A link to a downloadable version of the dataset or simulation environment.
    3. An explanation of any data that were excluded, description of any pre-processing step.
    4. An explanation of how samples were allocated for training / validation / testing.
    5. The range of hyper-parameters considered, method to select the best hyper-parameter configuration, and specification of all hyper-parameters used to generate results.
    6. The exact number of evaluation runs.
    7. A description of how experiments were run.
    8. A clear definition of the specific measure or statistics used to report results.
    9. Clearly defined error bars.
    10. A description of results with central tendency (e.g., mean) & variation (e.g., stddev).
    11. A description of the computing infrastructure used.




## Author Response

Authors will be given the opportunity to respond to their reviews before decisions are made. This is to enable them to address misunderstandings, point out parts of their submissions that were overlooked, or disagree with the reviewers’ assessments. In previous years, some authors felt that their responses were ignored. As a reviewer, it is your responsibility to read and (if appropriate) respond to each author’s response. It is not fair to ignore any author response, even for submissions that you think should be rejected. Although it is possible that an author’s response will not change your assessment of a submission, you must convey to the authors that you have carefully considered their comments. As you read each author’s response, keep an open mind. Have you overlooked something? Please update each review to indicate that you have read the author's response and whether you agree or disagree with it. You should be more specific than “I have read the author’s response and my opinion remains the same.” If that is the case, you should explain why it remains the same, what the author's response failed to address, etc.


LaTeX files for writing a response to reviewers are available on the [AISTATS 2022]({{ "index.html" | relative_url }})  homepage ([click here to download the files](http://aistats.org/aistats2022/AISTATS2022_Author_Response_Pack.zip)). 
Author responses are due Friday, December 3, 2021 at 11:59 AM UTC.
