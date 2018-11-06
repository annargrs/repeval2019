.. hidetitle: True

MultiEval shared task
=====================

MultiEval shared task will target classical sense-agnostic word
embeddings with an unconventional combination of intrinsic and extrinsic
methods.

The surprisingly-still-default intrinsic evaluation methods for
word-level models are similarity/relatedness and analogy tasks, but we
now know that they both have methodological issues
`[1] <https://doi.org/10.18653/v1/W16-2507>`__
`[2] <http://www.aclweb.org/anthology/S17-1017>`__, and there are
questions about their predictive power
`[3] <https://www.aclweb.org/anthology/W/W16/W16-2501.pdf>`__. Ideally,
intrinsic evaluations should be not a thing in themselves, but something
that can help to predict and explain the model’s behavior on downstream
tasks, and also guide the development of new models.

MultiEval will include a new set of intrinsic measures such as
specialization for a specific lexical relation, ability to capture
relations between words in the absence of direct distributional
evidence, the tendency to have related words very close together or more
spaced out. The participating systems will be profiled for 20 such
properties with the new LDT library
`[4] <http://aclweb.org/anthology/C18-1228>`__, which samples vector
neighborhoods for a given vocabulary sample and makes use of various
resources to detect lexicographic, morphological, associative and
distributional relations between neighbors of each word. This enables
quantitative/qualitative analysis of what information is prioritized by
the given model.

In addition to LDT intrinsic profiles, the participating systems will
also be evaluated on a suite of extrinsic tasks. The extrinsic tasks
will be picked to be representative and targeting various kinds of
information. At least the following tasks will be included: POS-tagging,
named entity recognition, chunking, sentiment analysis, relation
classification, natural language inference, question answering. There
will be separate categories in which a participating system can “win”:
morphological tasks (sequence labeling), semantic classification tasks
(sentiment analysis, relation classification), and high-level reasoning
tasks (inference, question answering).

The MultiEval combination of extrinsic and intrinsic scores should not
only provide a sophisticated leaderboard, but also yield insights into
patterns of gains/drops in accuracy vis-a-vis properties of
representations. This should stimulate discussion on ways to further
improve representations, and whether it is possible in principle to
reach the best performance on all kinds of tasks. The `proof-of-concept
correlation data <http://ldtoolkit.space/analysis/correlation>`__ for 60
word2vec and Glove models, and 14 extrinsic and intrinsic datasets
suggests that prioritizing morphological information is beneficial for
tasks like sequence labeling, but harms semantic tasks.

After the workshop the complete MultiEval setup will be released as a
single easy-to-run evaluation package in `Vecto <http://vecto.space>`__,
an open-source library for reproducible research on distributional
meaning representations.
