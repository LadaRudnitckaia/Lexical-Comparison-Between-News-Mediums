# Lexical-Comparison-Between-News-Mediums
Lexical Comparison Between News Mediums by Using Word Embeddings for Media Bias Identification

<img src="https://github.com/LadaRudnitckaia/Lexical-Comparison-Between-News-Mediums/blob/master/Lexicon%20analysis/nut_context.png" width="400">

![context](https://github.com/LadaRudnitckaia/Lexical-Comparison-Between-News-Mediums/blob/master/Lexicon%20analysis/nut_context.png)

### Data
The PostgreSQL database containing vast number of various news articles was provided by the Data & Knowledge Engineering Group of the University of Wuppertal.

### Codes
Preprocessing_and_training.ipynb contains data exploration, pre-processing and word embeddings training.
Lexical_comparison.ipynb contains linear mapping matrix training and lexical comparison.

### Lexicon analysis
The folder contains files that were used for manual analysis of distant words, of top 20 most similar to controversial and bias words and distances (pure and adjusted cosine similarities) for the common vocabulary.

### Models
Folder contains Word2Vec models trained on HuffPost articles, Breitbart articles as well as vectors from HuffPost mapped to Breitbart.
