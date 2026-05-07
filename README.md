# Toxic Text Classification using Traditional ML, LSTM, and BERT
This project compares multiple machine learning and deep learning architectures for toxic text classification. 

The study evaluates:
- Traditional Machine Learning Models
- Deep Learning Models
- Transformer-Based Models
It also analyzes the impact of text preprocessing on model performance.
## Objectives

- Detect toxic comments from online text
- Compare Logistic Regression, SVM, LSTM, and BERT
- Analyze preprocessing impact
- Compare accuracy, F1-score, and training efficiency
- ## Dataset

Dataset Used:
- Jigsaw Toxic Comment Classification Dataset (https://huggingface.co/datasets/thesofakillers/jigsaw-toxic-comment-classification-challenge)

Dataset Characteristics:
- Multi-label toxic comment dataset
- User-generated online comments
- Contains noisy and informal text
- Includes labels such as:
  - toxic
  - severe_toxic
  - obscene
  - threat
  - insult
  - identity_hate
## Text Preprocessing

The following preprocessing techniques were applied:

- Lowercasing
- URL removal
- Mention removal
- Emoji handling
- Repeated character normalization
- Punctuation removal
- Contraction expansion
- Obscene word normalization
## Models

### Traditional Machine Learning
- Logistic Regression
- Support Vector Machine (SVM)

Feature Extraction:
- TF-IDF Vectorization

### Deep Learning
- LSTM

### Transformer Model
- BERT
## Experimental Setup

The models were trained under two conditions:
1. Raw Text
2. Preprocessed Text

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-score
