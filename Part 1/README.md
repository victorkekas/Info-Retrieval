# Info-Retrieval

Team members: Georgios Viktor Kekas - Thanasi Prifti

This project implements a basic information retrieval system using Elasticsearch. It includes classical vector space search as well as query expansion using synonyms from WordNet and word2vec.

All code is in the `main.ipynb` notebook. The dataset used is [TREC-COVID](https://public.ukp.informatik.tu-darmstadt.de/thakur/BEIR/datasets/trec-covid.zip).

## How to Run

1. Install the required Python packages:
   ```bash
   pip install pandas nltk gensim elasticsearch