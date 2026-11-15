# Hadith Semantic Similarity System Using AraBERT

An Arabic semantic retrieval system that identifies Hadiths with similar meanings using **AraBERTv2 and SimCSE contrastive learning**.

## Methodology
- Matn extraction and text preprocessing
- AraBERTv2 contextual embeddings
- SimCSE contrastive fine-tuning
- Doc2Vec baseline comparison
- Cosine similarity for semantic retrieval
- KNN and Top-K evaluation

## Dataset
- Sahih Al-Bukhari
- 16 selected chapters
- 2,429 processed Hadiths
- Chapter-based positive and negative training pairs

[Original Kaggle Dataset](https://www.kaggle.com/datasets/fahd09/hadith-dataset)

## Results

| Metric | Doc2Vec | AraBERT-SimCSE |
|---|---:|---:|
| KNN Accuracy | 0.3530 | 0.6690 |
| Top-1 Accuracy | 0.1075 | 0.5113 |
| Top-5 Accuracy | 0.3713 | 0.7723 |
| Top-15 Accuracy | 0.6793 | 0.8827 |

## Technologies
Python · PyTorch · AraBERT · SimCSE · Sentence Transformers · Gensim · Scikit-learn

## Repository Contents
- `nlp-pro (7).ipynb` – Implementation and experiments
- `Association_for_Computational_Linguistics__ACL__conference.pdf` – Research paper

## Team
- Jood Alharbi
- Sarah Aldarwish
- Jana AlZobidi
- Joori Shareef
