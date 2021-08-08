# BERT-CQA
Building BERT-based QA System from CQA Dataset: Assessing Gender Bias

## The Classifier-Retriever Pipeline
- The BERT-based question classifier built by fine-tuning the pre-trained [BERT model](https://huggingface.co/bert-base-uncased) using QA dataset.
- The answer retriever built by using the [BERT-based semantic similarity algorithm](https://huggingface.co/sentence-transformers/bert-base-nli-stsb-mean-tokens).

## Data Description

- [Categories Description](data_description/CQA_dataset-Dataset_Description.csv)
- [The Number of QA Pairs by Topic](data_description/data_170.csv)
- [The Number of QA Pairs by Topic and Category](data_description/data_3.csv)

## Output of the Experiments

- [Sample Question Answering Results](output/result_sample.csv)
- [Bias in Gender Distrbutions](output/gender_distribution.csv)
