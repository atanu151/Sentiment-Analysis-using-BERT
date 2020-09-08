# Aspect Category Sentiment Analysis on a Challenging Dataset
The advanced world with the internet makes everyone
enable to provide his/her opinion, and a review depicts
the sentiment of a user towards various aspects of a product
or service. Aspect-Category Sentiment Analysis (ACSA) aims to
predict the pre-defined aspect categories present in a review and
their respective sentiment polarities. Most sentences in current
ACSA datasets contain only one category or multiple categories
of the same sentiment polarity, which causes ACSA tasks to
deteriorate into sentence-level analysis of sentiment. In this
paper, we have performed experiments on a large-scale Multi-
Aspect Multi-Sentiment (MAMS) dataset, where each sentence
consists of at least two different aspect categories with different
sentiment polarities. As traditional word representations of the
sentences will not produce good results on such a dataset,
we have experimented with CNN and BERT classifiers using
context-independent and context-dependent word embeddings
respectively. They have achieved competitive results on the
MAMS dataset as well as SemEval-2014 Restaurant Review
Dataset for the Aspect Category Detection (ACD) task. The
BERT classifier outperforms the best submission of SemEval-
2014 for ACD, and it proves that the use of contextual word
embedding is the most effective method for this task. We
also presented an attention-based Long Short-Term Memory
(LSTM) Network for Aspect Category Sentiment Classification
(ACSC). The mechanism concentrates on multiple parts of a
given sentence when multiple aspects are used as input. Using
LSTM architecture, we observed that assigning weights to the
concerned aspects helps in utilizing all the elements present in a
sentence. As part of our paper, we try to demonstrate adequate
performance of the LSTM mechanism for ACSC.
