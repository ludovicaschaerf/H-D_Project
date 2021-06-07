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

The ipython notebook instances each contain the corpus loading, preprocessing and tfidf vectorization for each of the three corpus based extractions (still need propaganda one). (need a notebook containing the city names searches). Each of the notebooks, in addition, contains the plots obtained from querying the words into the impresso website, under the [ngrams tab](https://impresso-project.ch/app/search/ngrams?sq=CgcYCSoDR0RMCgIYAgoOEAIYByABKgZuYXRpb24%3D). The remaining folders contain the data loaded by the notebooks.

## Project Abstract

In our project we would like to trace the emergence of Swiss identity by looking at regional Swiss newspapers over the course of a century. We chose to consider newspapers in as much as they largely reflect and model the opinions and topics of interest to the regional population. We would like to start our investigation by modeling and tracking inter-regional interest and national sentiment shown by local newspapers over the long term. Then, we would expand our investigation by tracing several textual proxies for Swiss identity in the newspapers. Those proxies would consist of: 1) extracting the conceptualization of Swiss identity from early Swiss history books and trying to trace the evolution of those concepts in the newspapers. 2) Analyzing sociology papers on Swiss nationalism and extracting the constructed paradigm of Swiss identity. 3) Extracting World War I propaganda from the newspapers themselves and using the propaganda as a proxy of patriotism.
All presented proxies are probably inherently biased and might not work as wished. However, by looking at the question of identifying national identity from several angles and by taking different proxies into account, we hope to produce meaningful and robust results.
