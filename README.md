# DANN: Data Augmentation with Nearest Neighbor Classifier for Few-shot Named Entity Recognition

## Overview

DANN (Data Augmentation with Nearest Neighbor Classifier) is a novel approach designed to enhance few-shot learning (FSL) in Named Entity Recognition (NER) within the biomedical domain. The model combines semantic data augmentation with a nearest neighbor classification strategy, addressing data sparsity issues commonly found in medical NLP tasks.

Notebooks for medical named entity recognition with DANN model, used in the article "**Data Augmentation with Nearest Neighbor Classifier for Few-shot Named Entity Recognition**" which was published in the MedInfo 2022.

Update (2024): The preprocessed data available

## Features

**Few-shot Learning:** Efficiently learns from small labeled datasets, crucial for tasks with limited annotated medical data.

**Semantic Data Augmentation:** Enhances input token representations using similar words identified through cosine similarity.

**Nearest Neighbor Classification:** Employs multiple distance metrics (e.g., Manhattan, Euclidean) to improve entity detection accuracy.

## Workspace requirements

• Python 3.7+  
• Pytorch 2.2+  
• Huggingface Transformers (tested with version 3.1)  
• FastNLP (tested with version 0.5)  
• Word2vec (tested with version 0.9.4)  
• Numpy (tested with version 1.17.4)  
• Pandas (tested with version 0.20)  
• Seqeval (tested with version 0.12)  
• Spacy (tested with version 3.5)  
• Tqdm (tested with version 4.48)  
• A Graphical Processing Unit (GPU)

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
## Acknowledgements

These code is inspired by the following resources:

https://github.com/Spain-AI/transformers (by Álvaro Barbero)

https://github.com/cuhksz-nlp/SANER (by CUHK-SZ NLP Group)

https://github.com/fastnlp/fastNLP (by NLP team at Fudan University)

## How to cite

If you use this code, you can make reference to the article where the script was made available, as follows:

*Yao Ge, Mohammed Ali Al-Garadi, Abeed Sarker. "[Data Augmentation with Nearest Neighbor Classifier for Few-Shot Named Entity Recognition.](https://ebooks.iospress.nl/doi/10.3233/SHTI231053)" MEDINFO 2023—The Future Is Accessible, pages: 690-694. 2023. doi: 10.3233/SHTI231053. PMID: 38269897.*

```bibtex
@incollection{ge2024data,
  title={Data Augmentation with Nearest Neighbor Classifier for Few-Shot Named Entity Recognition},
  author={Ge, Yao and Al-Garadi, Mohammed Ali and Sarker, Abeed},
  booktitle={MEDINFO 2023—The Future Is Accessible},
  pages={690--694},
  year={2024},
  publisher={IOS Press}
}

