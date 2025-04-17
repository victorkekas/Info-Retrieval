# Info-Retrieval

# 🔍 Query Expansion with Synonyms for Information Retrieval

This project implements a search engine using classical and modern Information Retrieval techniques to enhance query results through synonym expansion. The engine is built with Python and Elasticsearch and evaluated on the [TREC-COVID](https://public.ukp.informatik.tu-darmstadt.de/thakur/BEIR/datasets/trec-covid.zip) dataset.

## 📁 Project Structure

- `data/` – Folder containing the dataset files (`corpus.jsonl`, `queries.jsonl`, `qrels/test.tsv`)
- `preprocessing.py` – Script to load, clean, and prepare the documents.
- `indexing.py` – Script to create the index in Elasticsearch and bulk upload documents.
- `search.py` – Script to run the search queries.
- `evaluation/` – Scripts and results from `trec_eval`.
- `README.md` – Project description and usage guide.

## 🚀 Features

- Classical Vector Space retrieval (ElasticSearch-based)
- Query expansion using:
  - WordNet (NLTK)
  - Word2Vec (Gensim)
- Evaluation with TREC Eval (MAP, Precision@K)

