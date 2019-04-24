---
# layout: page
title: CFP
permalink: /cfp/
---

# <span style="color:#267CB9"> Call for papers</span>

General-purpose dense word embeddings have come a long way since the beginning of their boom in 2013, and they are still the most widely used way of representing words in both industrial and academic NLP systems. However, the issue of intrinsic metrics that are predictive of performance on downstream tasks, and can help to develop better representations, is far from being solved. At the sentence level and above, we now have a number of probing tasks and large extrinsic evaluation datasets targeting high-level verbal reasoning, but there is still much to learn about what features make a compositional representation successful. Last but not the least, there are no established intrinsic methods for newer kinds of representations such as ELMO, BERT, or box embeddings.

The third edition of RepEval aims to foster discussion of the above issues, and to support the search for high-quality general purpose representation learning techniques for NLP. We hope to encourage interdisciplinary dialogue by welcoming diverse perspectives on the above issues: submissions may focus on properties of embedding space, performance analysis for various downstream tasks, as well as approaches based on linguistic and psychological data. In particular, experts from the latter fields are encouraged to contribute analysis of claims previously made in NLP community.

## <span style="color:#267CB9"> Topics</span>

RepEval 2019 invites submissions including, but not limited to the following issues:

- approaches to intrinsic and extrinsic evaluation of all kinds of representations, esp. contextualized;
- evaluation motivated by linguistic, psycholinguistic or neurological evidence, its predictive power, and interpretability of meaning representations vs evaluation on downstream tasks;
- the (un)stability of vector representations, best practices for reproducible and reliable experiments;
- evaluation of representations at subword level, especially for morphologically complex languages;
- evaluation of phrase, sentence, paragraph and document-level representations: evidence of compositionality, further diagnostic tests, and how much the preservation of abstract syntactic information actually contributes to performance;
- formal analysis of properties of embedding spaces and their impact on downstream tasks;
- the effect of representations vs other elements of pipeline in extrinsic evaluations;
- validation of evaluation methodology and findings in cross-lingual studies;
- specialized vs general-purpose representations, and whether the latter have inherent limits in downstream tasks;
- internal states of end-to-end systems as meaning representations, and ways to make more sense of them.

## <span style="color:#267CB9"> Submission Types and Requirements </span>

Research paper submissions may consist of 4-6 pages of content, plus unlimited references. An additional page in the camera-ready version will be available for addressing reviewers’ comments. Please refer to the NAACL author guidelines for the style files, policy on double submissions and preprints: https://naacl2019.org/calls/papers/#author-guidelines

We invite proposals for new evaluation techniques for old and new representations; the submissions are expected to experimentally demonstrate the benefits of the new approach. Submissions may also contribute critical analysis and/or negative results for the existing approaches. 

We welcome both theoretical analysis (especially from experts in other domains such as linguistics or psychology) and methodological caveats (reproducibility, parameters impact, the issue of attribution of results to the representation or the whole system, dataset structure/balance/representativeness).

Theoretical papers might like to consider the following questions:

- What are the pros and cons of existing evaluations?
- What are the limitations of task-independent representation or its evaluation?
- (Mis)attribution of performance improvements to various elements of the pipeline in complex NLP systems;
- Given a specific downstream application, which existing evaluation (or family of evaluations) is a good predictor of performance improvement?
- Which linguistic/semantic/psychological properties are captured by existing evaluations? Which are not?
- What methodological mistakes were made in the creation of existing evaluation datasets?
- What linguistic/psychological properties of meaning representations are supposed to make them "better", and why?
- The recent tendency is to take high-level reasoning tasks such as QA or inference as the "ultimate" evaluation for meaning representations (effectively, a Turing test proxy). How justified is this approach? Should a "good" representation excel at all such tasks, or specialize? What alternatives do we have?

Proposal papers should introduce a novel method for evaluating representations, accompanied with a proof-of-concept dataset (of which at least a sample should be made available to the reviewers at the submission time). The new method should highlight some previously unnoticed properties of the target representations, or enables a faster/more cost-effective way of measuring some previously known properties. We also invite proposals that can demonstrate a significant improvement to the previous metrics (e.g. update to an imbalanced or noisy dataset that shows that previous claims were misattributed).

Each proposal should explicitly mention:

- Which type of representation it evaluates (e.g. word, sentence, document, contextualized or not), and what specific properties of that representation it targets;
- For which downstream application(s) it functions as a proxy;
- Any linguistic/semantic/psychological properties it captures, in comparison with previous work;
- If any annotation was performed, what was the inter-annotator agreement, and how cost-effective would it be to scale it up and/or create a similar resource for other languages?
- If the dataset collection involved human participants, personally identifiable information, social media or web data, please include the relevant details for the institutional review, license terms and permissions to use/release the data.

## <span style="color:#267CB9"> Shared task</span>

RepEval 2019 shared task has been cancelled. 

## <span style="color:#267CB9"> Paper Submission </span>

Submission is electronic, using the Softconf START conference management at https://www.softconf.com/naacl2019/repeval/

All accepted papers must be presented at the workshop to appear in the proceedings. At least one author of each accepted paper must register for the workshop by the early registration deadline. Previous presentations of the work (e.g. preprints on arXiv.org) should be indicated in a footnote that should be excluded from the review submission, but included in the final version of papers appearing in the NAACL-HLT 2019 proceedings.

## <span style="color:#267CB9"> Important Dates</span>

- ~~First call for workshop papers: December 22, 2018~~

- ~~Second call for workshop papers: January 15, 2019~~

- ~~Workshop papers due: March 8, 2019 (extended)~~

- ~~Notification of acceptance: March 29, 2019 (extended)~~

- ~~Camera-ready papers due: April 5, 2019~~

- Workshop date: June 6, 2019

All deadlines are 11.59 pm UTC -12h.

## <span style="color:#267CB9"> Contact Information</span>

Email: repeval2019@googlegroups.com
