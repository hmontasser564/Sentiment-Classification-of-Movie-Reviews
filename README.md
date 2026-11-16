# IMDb Movie Review Sentiment Classification

Assignment 2 — Text classification with **TF-IDF** and **Logistic Regression**.

The notebook classifies IMDb movie reviews as positive or negative.

## Pipeline

Raw reviews → text preprocessing → train/test split (80/20, stratified) → TF-IDF (unigrams + bigrams) → Logistic Regression → predictions → evaluation

## Dataset

[IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) (Kaggle).

The CSV is not included in this repository because of its size (~66 MB). Download it and place `IMDB Dataset.csv` in the same folder as the notebook.

## How to run

```bash
pip install -r requirements.txt
jupyter notebook Assignment_2_IMDB_Sentiment.ipynb
```

## Results (test set)

| Metric    | Score  |
|-----------|--------|
| Accuracy  | 0.8998 |
| Precision | 0.8884 |
| Recall    | 0.9152 |
| F1-score  | 0.9016 |

The notebook also includes a confusion matrix and predictions on new example reviews.

## Files

- `Assignment_2_IMDB_Sentiment.ipynb` — the full notebook
- `Assignment 2.pdf` — the assignment description
- `requirements.txt` — Python dependencies
