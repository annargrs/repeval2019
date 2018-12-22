---
title: MultiEval Shared Task
permalink: /task/
---

# MultiEval shared task

MultiEval shared task will combine a wide range of intrinsic and extrinsic methods to evaluate word embedding models. The goal of this task is to not only find the “winners”, but also to identify intrinsic measures that are useful for explaining/predicting downstream task performance.
Submitted word embedding models will be trained on the corpus provided by the organizers, which will be made available on January 24th. 

The extrinsic evaluation will consist of a suite of NLP tasks picked to target different kinds of information. The following tasks will be included: 

- POS-tagging, named entity recognition, chunking (CoNLL shared task datasets), 
- sentiment analysis (MR dataset of short movie reviews, Pang and Lee, 2005), 
- relation classification (SemEval 2010 task 8 dataset, Hendrickx et al., 2010), 
- natural language inference (SNLI dataset, Bowman et al., 2015).

The implementations for these tasks will be made available by January 24th, and the participants can use them for fine-tuning their systems. There will be also several “surprise” tasks/datasets, which will only be made public after the results are announced. The complete set of MultiEval tasks will be subsequently released as a single evaluation package in Vecto, an open-source library for reproducible research on distributional meaning representations.

The intrinsic evaluation will be performed using the new [LDT library](http://ldtoolkit.space), which includes over 20 intrinsic measures (including specialization for different lexical relations such as synonyms or antonyms, and ability to capture relations between words in the absence of direct distributional evidence). LDT extracts vector neighborhoods for a given vocabulary sample and quantifies lexicographic, morphological, associative and distributional relations in vector neighborhoods with a variety of dictionary resources. This information [can be used to explain the performance of the model and fine-tune it for different extrinsic tasks](http://ldtoolkit.space/analysis/correlation/). On January 24th we will provide the vocabulary sample that can be used for development; the final test vocabulary will be different.

By combining intrinsic and extrinsic evaluation the MultiEval leaderboard will aim to provide insights into accuracy gains vis-a-vis different properties of embedding models. At the moment it is not clear whether it is possible in principle to “win” on all scores and all tasks. There will be separate nominations for the best-performing representation across different groups of extrinsic tasks (morphological, semantic, high-level reasoning), as well as the best generalist representation that performs well across the whole range of tasks without falling too far behind the top specialized models.

# Important dates

- Training corpus and data released: January 24, 2019

- Shared task submissions due: February 24, 2019

- Shared task results announced: before February 28, 2019

