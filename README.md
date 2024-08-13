## Overview
In this repository, biomedical text was processed through various NLP models. Text was extracted and labeled with NLTK, SciSpaCy, and BPE methods. Word representations were created using N-gram, Skip-gram, and MLM models to understand relationships between biological terms. Finally, T-SNE was applied for matrix visualization, showing data readability. The experiments demonstrate strong performance of these NLP models on medical texts.

## Dataset Introduction
For the dataset, I use CORD-19, which is a corpus of academic papers about COVID-19 and related coronavirus research. It’s curated and maintained by the Semantic Scholar team at the Allen Institute for AI to support text mining and NLP research.The detail of this dataset can be found in [CORD-19](https://huggingface.co/datasets/allenai/cord19).

## Part I. Data Processing
- Loading and parsing data using json and jsonpath modules.
- Text Tokenization by split(), NLTK and BPE.
- Analize the advantages and disadvantages of each method.
  
## Part II. Word Representation Models
- N-gram Model: A fundamental method for constructing word vectors.
- Skip-gram Model: Used for predicting the context of words.
- Masked Language Model (MLM): Involves predicting masked words from the context during training.
- Optimazing the model by negative sampling and subsampling techniques to improve training efficiency.

## Part III. Visualization of Word Representations
- Utilizing t-SNE for dimensionality reduction and visualization of word representations.
- Applying k-means clustering for visualizing biomedical entities.

 ## Part IV. Word Vector Analysis
- Co-occurrence Analysis: Identifying words semantically close to specific terms (e.g., "coronavirus").
- Semantic Similarity: Measuring the similarity between words using cosine similarity.
- Building a knowledge graph to intuitively represent relationships between biomedical entities based on textual descriptions.
