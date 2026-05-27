# MLOps Assignment 2 — Hugging Face Fine-Tuning, Experiment Tracking & Model Deployment

Fine-tuned DistilBERT on Goodreads reviews to classify book genres, with experiment tracking via Weights & Biases and model deployment to Hugging Face Hub.

## Model
- Base model: `distilbert-base-uncased`
- Dataset: UCSD Goodreads Reviews (8 genres)
- Framework: HuggingFace Transformers + W&B

## Results

| Metric | Score |
|--------|-------|
| Accuracy | 61.125% |
| F1 (weighted) | 61.186% |
| Precision | 61.37% |
| Recall | 61.125% |

## Links
- Kaggle Notebook: https://www.kaggle.com/code/dhruvig25ait2030/mlops-assignment2
- Hugging Face Model: https://huggingface.co/Doobieeeful/distilbert-genre-classification
- W&B Dashboard: https://wandb.ai/g25ait2030-prom-iit-rajasthan/mlops-assignment2
