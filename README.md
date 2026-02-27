# Data-science-project
Research Methods in Data Science project: End-to-end machine learning pipeline including data preprocessing, model selection, hyperparameter optimisation, evaluation metrics, and reproducible version tracking.

## Dataset

his project uses the **IMDb Dataset of 50K Movie Reviews** from Kaggle.

- **Dataset source:**  
  https://www.kaggle.com/datasets/mdraselsarker/imdb-dataset-of-50k-movie-reviews

- **Description:**  
  This dataset contains 50,000 movie reviews labeled as *positive* or *negative*. It is a commonly used benchmark dataset for binary sentiment classification in natural language processing.

- **Columns:**
  | Column   | Description |
  |----------|-------------|
  | review   | The text of the movie review |
  | sentiment| Sentiment label (positive / negative) |

- **Original shape:** (50,000, 2)  
  **After cleaning (duplicates removed):** (49,582, 2)

- **Why full dataset is not included here:**  
  GitHub does not allow files larger than 25MB to be uploaded directly in the web interface. The dataset is larger than this limit and therefore is not included in the repository.

### How to use the dataset

1. Click the Kaggle link above.
2. Download the dataset (`IMDB Dataset.csv`).
3. Place the downloaded file in your project directory.
4. Run the notebook code (e.g., `sentiment_analysis.ipynb`) to train and evaluate the models.
