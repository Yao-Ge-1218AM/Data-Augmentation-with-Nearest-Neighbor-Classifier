# DANN: Data Augmentation with Nearest Neighbor Classifier for Few-shot Named Entity Recognition

## Overview

DANN (Data Augmentation with Nearest Neighbor Classifier) is a novel approach designed to enhance few-shot learning (FSL) in Named Entity Recognition (NER) within the biomedical domain. The model combines semantic data augmentation with a nearest neighbor classification strategy, addressing data sparsity issues commonly found in medical NLP tasks.

Notebooks for medical named entity recognition with DANN model, used in the article "**Data Augmentation with Nearest Neighbor Classifier for Few-shot Named Entity Recognition**" which was published in the MedInfo 2022.

Update (2024): The annotated data and the BERT trained model is now available

## Features

**Few-shot Learning:** Efficiently learns from small labeled datasets, crucial for tasks with limited annotated medical data.
**Semantic Data Augmentation:** Enhances input token representations using similar words identified through cosine similarity.
**Nearest Neighbor Classification:** Employs multiple distance metrics (e.g., Manhattan, Euclidean) to improve entity detection accuracy.

## Workspace requirements

Python 3.7+
Pytorch 2.2+
Huggingface Transformers (tested with version 3.1)
fastNLP (tested with version 0.5)
word2vec (tested with version 0.9.4)
Numpy (tested with version 1.17.4)
Pandas (tested with version 0.20)
Seqeval (tested with version 0.12)
spacy (tested with version 3.5)
tqdm (tested with version 4.48)
A Graphical Processing Unit (GPU)

## Installation

To set up the DANN model, follow these steps:
#### Clone the repository
```bash
# Clone the repository
git clone https://github.com/yourusername/dann-ner.git

# Navigate to the project directory
cd dann-ner

# Install dependencies
pip install -r requirements.txt
```

