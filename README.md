\# Amazon Reviews Sentiment Analysis



Sentiment classification on the Amazon Reviews dataset using multiple representations and models.



\## Features

\- Word2Vec embeddings

\- TF-IDF features

\- MLP and CNN baselines

\- Training/evaluation pipeline with F1, precision, recall

\- Debug prints for inspection during training



\## Quickstart (after code is added)

```bash

python -m venv .venv \&\& .\\.venv\\Scripts\\activate  # Windows

pip install -r requirements.txt



\# Example training run

python src/train.py --model mlp --epochs 5



