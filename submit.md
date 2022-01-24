--- 
title: Camera Ready 
layout: default 
weight: 7 
---


# Instructions for Camera-Ready Paper


Please take some time to read these instructions **in full**. For your
camera-ready paper to be included in the proceedings, it is **essential** that
you follow the instructions contained on this page.


## Deadline


The deadline for the camera-ready submission is **Wednesday, February 23rd,
2022, 11:59am UTC**. This is a strict deadline, so please be aware of the time
zone and take into account that it is **AM** and _not_ PM. You may find it useful to
use an online time converter like this one:
<https://www.timeanddate.com/worldclock/converter.html?iso=20220223T115900&p1=tz_jst&p2=tz_hkt&p3=1440&p4=tz_et&p5=tz_pt>


No extensions to the deadline will be granted in any cases. If you miss the
deadline, your paper will not be included in the proceedings. We strongly
recommend submitting your camera-ready version well in advance of this
deadline.


## Submission instructions


You have to upload one PDF file (mandatory), one PDF filled and signed
copyright form (mandatory), and one ZIP file containing the non-textual
supplementary material (optional).


1) **PDF file (mandatory).** The PDF file must contain the paper, including the
references and acknowledgements, and optionally the textual supplementary
material. **Differently from the initial submission**, now the textual
supplementary material ("the appendix") **must** follow the paper content (after
Acknowledgements and References) in the **same PDF file**. You will also have to
obtain a submission code from the paper style checker by uploading this PDF
file to 
<https://research.engineering.wustl.edu/machinelearning/pub/AISTATS2022> 
(see [Submission to CMT](#submission-to-cmt) for details).


The PDF file should be **named 642.pdf**, with 642 replaced with your submission ID
on CMT.


To prepare your camera-ready PDF paper, please check the following formatting
instructions:


1. Please use the **UPDATED** LaTeX style file available at:
   <http://aistats.org/aistats2022/AISTATS2022CameraReadyPaperPack.zip>.
2. Use the **NEW `sample_paper.tex`** file as the starting file for your submission,
   as it contains some important changes.
3. Camera-ready submissions are **limited to 9 pages**, excluding acknowledgements,
   references, and (optionally) textual supplementary material. Please use the
   additional 9th page to address the reviewers’ and meta-reviewer’s feedback,
   which we request you to take into account.
4. The main paper and the textual supplementary material ("Appendix"), if any,
   must now be submitted as a **single PDF** instead of two separate files.
5. Do not change the style file, including spacing. If you have questions about
   the style file or its usage, please contact the 
   [Publications Chair](https://sghalebikesabi.github.io/).
6. Your paper must use **US letter** format (default in the style file). Do 
   **not** change this to A4 paper format.
7. You must use the **default LaTeX font**; please don’t change it.  For
   example, do **NOT** include the line `\usepackage{times}` used in other
   conferences (e.g., ICML, NeurIPS, or ICLR). In addition, please **avoid
   using Type 3 fonts** anywhere in your document, including in embedded
   images. See
   <https://www.ics.uci.edu/~chenli/pdf-font-types/index.html>
   for more information.
8. Please use **ALL CAPS section headings**, as detailed in the latex templates.
9. Citations **must** be in the **“(Author, Year)” format**, e.g., (Cheesman, 1985). To
   achieve that, you may use the `natbib` latex package (or any other similar one
   that achieves the same purpose). Be sure that the sentence reads correctly
   if the citation is deleted; e.g., instead of “As described by (Cheesman,
   1985), we first frobulate the widgets,” write “As described by Cheesman
   (1985), we first frobulate the widgets.”
10. The paper must be **de-anonymized**, i.e., the author names and institutions
    should be visible. For that, please make sure to use
    `\usepackage[accepted]{aistats2022}` when loading the style file.
11. The acknowledgements section should be titled "Acknowledgments".
    Acknowledgements are optional, but if your paper contains this section, it
    must appear before the References.
12. The reference section should be titled "References". The references listed
    at the end of the paper can follow any style as long as it is used
    consistently.
13. Please consider the following colorblind-friendly guidelines for
    introducing color in your figures and plots:
    <https://usabilla.com/blog/how-to-design-for-color-blindness>.
14. Further formatting instructions can be found in the `sample_paper.pdf` file
    available at
    <http://aistats.org/aistats2022/AISTATS2022CameraReadyPaperPack.zip>.


2) **Copyright form (mandatory)**. Please download the PMLR copyright form,
available at <http://proceedings.mlr.press/pmlr-license-agreement.pdf>, fill it
in, sign it, rename it as **642-Permission.pdf** (with 642 replaced by your
submission ID on CMT), and submit it with the rest of the documents. It is
sufficient for one author to sign the agreement on behalf of all authors.


3) **Non-textual supplementary material (optional)**. The **ZIP file** may contain any
**non-textual** supplementary material, such as code for the paper.


* Your supplementary material file should be named **642-supp.zip** (with 642
  replaced with your paper ID on CMT).
* If you wish to include any **code/datasets** as part of the supplementary
  material, you can: (i) include it in the ZIP file of your supplementary
  material, and/or (ii) provide the public URL where the code can be found in
  the appropriate field of CMT submission form.  **If you promised to release
  code/datasets** (either in the original submission PDF or during the rebuttal),
  **the code/dataset must be released**. In this case, the AISTATS Chairs will
  check the availability of the code/dataset and, if it isn’t available by the
  camera-ready deadline, your submission may be excluded from the conference
  proceedings.
* If you wish to include any **videos** as part of the supplementary material,
  please do **not** include them in the ZIP file. Instead, simply provide the
  public URL where the video is available in the appropriate field of the CMT
  submission form. **NOTE**: This does not refer to the recorded presentation
  explaining your paper, which will be submitted/recorded via Slideslive (see
  instructions below), but to any other videos containing, e.g., experimental
  results.
* Do **not** include any textual supplementary material in the ZIP file. It must be
  included in the same PDF as the main paper.




## How to avoid the most common formatting violations


* Please make sure any textual supplementary material ("the appendix") is
  submitted in the same file as the main paper.
* Your paper must **not exceed 9 pages**, except for acknowledgements, references,
  and (optionally) textual supplementary material.
* Your paper must be in **US letter size** (i.e., not A4 or other sizes).
* Your paper must use the default LaTeX font; e.g., the tex file should **NOT**
  contain the line `\usepackage{times}` or any other line that changes the font.
* Please ensure that your camera-ready submission contains author information
  (names and affiliations), instead of "Anonymous Author N" as was required for
  the original submission, and that the submitted list of authors and the
  ordering among them **matches the information on CMT**.


## Submission to CMT

Camera-ready submissions must be submitted via CMT:
<https://cmt3.research.microsoft.com/AISTATS2022>. If you are also a reviewer or
Area Chair, make sure that your role is set to “Author”. To change your role to
“Author,” click next to “Select Your Role” in the top right of the page.

In the CMT Author Console there is now a new link to "Create camera-ready
submission" for each accepted paper. Use this link to submit camera-ready
papers. The CMT form will ask you for the title, the abstract, the list of
authors (only changes to the author order are allowed at this point, as per the
submission agreement), and the following files (where 642 is to be replaced by
your submission ID): **642.pdf**, **642-Permission.pdf**, 
and **642-supp.zip (optional)**.

Please ensure that the submitted **title and abstract match the ones in the
camera-ready version**, and do not include any LaTeX commands or other
non-human-readable markup.

The final version will appear in the [PMLR
proceedings](https://proceedings.mlr.press/), published by JMLR W&CP. The CMT
will ask you to agree to have your work published by JMLR according to the
agreement outlined
[here](http://proceedings.mlr.press/pmlr-license-agreement.pdf).

You will also be asked to provide **a submission code obtained by an automated
style checker**. To obtain the code, please follow these steps: 

1. Go to
   <https://research.engineering.wustl.edu/machinelearning/pub/AISTATS2022> 
2. Provide the paper ID (from CMT), your name (just one author), your e-mail
   and the submission PDF file. If the paper passes the style checks, you will
obtain a submission code. (Please ignore the warnings of the style checker.)
**The submission code is only valid for this particular PDF file**. If you
further edit the PDF, you will need to obtain another submission code.  
3. When submitting your paper on CMT,  you need to provide the style checker
   submission code.

You may continue to edit your camera-ready submissions until the camera-ready
deadline.

We thank [Roman Garnett](https://www.cse.wustl.edu/~garnett/) for kindly
helping the AISTATS Chairs to set up and host the paper style checker. 

