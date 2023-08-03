# KIND_Pertino_Pesce_Sandri

The aim of the project is to apply the techniques learnt during the course of Natural Language Processing (NLP) to analyse the [KIND](https://github.com/dhfbk/KIND) dataset. The main task of this dataset is to perform Named-Entity-Recognition (NER) from Italian documents.

1. Preliminary analysis:
    - description and inspection with statistics of the dataset;
    - clustering of the documents and visualisation, using k-means and topic modelling;
    - indexing of the documents to perform keyword search over them using PyTerrier;
    - training of a Word2Vec and fastText embedding on the data and investigation of the resulting properties of the embedding.

2. Training models to perform NER:
    - training Conditional Random Fields models; 
    - testing pre-trained models using SpaCy and Stanza;
    - fine-tuning of BERT models (Italian-only, multilingual and English) from HuggingFace.
