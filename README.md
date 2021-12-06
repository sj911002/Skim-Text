# Skim-Text

In this project a series of deep learning experiments(NLP models) were developed to  perform sequential sentence classification on abstracts. The model takes unstructured abstracts and produces structured abstracts, i.e. the text in an abstract is divided into semantic headings (background, objective, method, result, and conclusion). The outcomes of this task enables researchers to skim through the literature and dive deeper when necessary.

Dataset: PubMed 200k RCT dataset

Modelling experiments:
1. Naive Bayes with TF-IDF Encoder (Accuracy: 71.66%)
2. Conv1D with custom token embeddings (Accuracy: 80.66%)
3. Conv1D with character embeddings (Accuracy: 70.83%)
4. Feature extraction with pre-trained token embeddings (Accuracy: 74.38%)
5. Model with hybrid embedding layer (pre-trained token embeddings + character embeddings)  (Accuracy: 75.50%)
6. Model with tribrid embedding layer (pre-trained token embeddings + character embeddings + positional embeddings) (Accuracy: 84.49%)
