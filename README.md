# Tracing Swiss National Sentiment in Newspapers

Repository for the DH-412 course project.
By Aurel Maeder, Ludovica Schaerf, Michal Bien.

## Organisation of the repository

```
.
+-- data                     - data files and data links used for the analysis
|  +-- corpus_analysis       - target and reference corpora used for TF-IDF extraction
|  +-- longitudinal_analysis - token frequency lists extracted from Impresso
+-- src                      - notebook used for each part of the analysis
+-- requirements.txt         - python environment requirements to run the notebooks
+-- README.md
```

The ipython notebook instances each contain the corpus loading, preprocessing and tfidf vectorization for each of the three corpus based extractions. Each of the notebooks, in addition, contains the plots obtained from querying the words into the impresso website, under the [ngrams tab](https://impresso-project.ch/app/search/ngrams?sq=CgcYCSoDR0RMCgIYAgoOEAIYByABKgZuYXRpb24%3D). The remaining folders contain the data loaded by the notebooks.

## Project Abstract

Swiss nationalism and national identity have been discussed by a rich body of literature from different scientific communities. In our analysis, we would like to contribute to this general discussion by tracing the evolution of Swiss national identity from the XIX century using computational methods. Specifically, we consider the period from the 1820s to the 1950s, when the formation and development of the modern Swiss Nation took place. This analysis aims to articulate the concept of Swiss nationality in a computer-understandable manner and to scan the vast corpus of regional Swiss newspapers for its evolution in time. Newspapers have been chosen as, we believe, they largely reflect and model the opinions and topics of interest to the regional population. To the best of our knowledge, the adoption of newspapers as a primary source has not yet been considered in the analysis of Swiss nationality and could hopefully provide new insights into the matter.
