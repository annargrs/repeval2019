---
title: MultiEval Shared Task
permalink: /task/
---

# MultiEval shared task

MultiEval shared task will combine a wide range of intrinsic and extrinsic methods to evaluate word embedding models. The goal of this task is to not only find the "winners", but also to identify intrinsic measures that are useful for explaining/predicting downstream task performance. 

Submitted word embedding models will be trained on the corpus provided by the organizers. The intrinsic evaluation will be performed using the new [LDT library](http://ldtoolkit.space), which includes over 20 intrinsic measures (including specialization for different lexical relations such as synonyms or antonyms, and ability to capture relations between words in the absence of direct distributional evidence). LDT extracts vector neighborhoods for a given vocabulary sample and detects lexicographic, morphological, associative and distributional relations between neighbors of each word with a variety of dictionary resources. This enables both quantitative and qualitative analysis of the information prioritized by each embedding model.

The extrinsic evaluation will consist of a suite of NLP tasks picked to target different kinds of information.  The following tasks will be included: POS-tagging, named entity recognition, chunking, sentiment analysis, relation classification, natural language inference, question answering. There will be several categories in which a participating embedding model can "win", including (a) morphological tasks (sequence labeling), (b) semantic classification tasks (sentiment analysis, relation classification), and (c) high-level reasoning tasks (inference, question answering). 

The shared task will provide a leaderboard for different extrinsic and intrinsic scores, yielding insights into accuracy gains vis-a-vis different properties of embedding models. At the moment it is not clear whether it is possible in principle to "win" on all scores and all tasks. There will be a separate nomination for the best generalist representation that performs well across the whole range of tasks without falling too far behind the top specialized models.

The complete set of MultiEval tasks will be subsequently released as a single evaluation package in [Vecto](http://vecto.space), an open-source library for reproducible research on distributional meaning representations.