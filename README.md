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

## 📄 Sample dataset 

A smaller sample (`dataset_sample.csv`) is included for quick testing. This is a representative subset of 5,000 reviews.

## Machine Learning Models Used

The following classical machine learning models were implemented and compared:

1.Logistic Regression

2.Linear Support Vector Machine (SVM)

3.Multinomial Naive Bayes

4.Random Forest

## Feature Engineering

Text data was converted into numerical features using TF-IDF (Term Frequency – Inverse Document Frequency) vectorisation.

This allows machine learning models to process text data by transforming words into weighted numerical representations.

## Evaluation Metrics

Model performance was evaluated using multiple metrics:

* Accuracy

* F1-score

* Cross-validation score

* ROC-AUC score

* Classification report (precision, recall, F1-score)

These metrics provide a comprehensive evaluation of classification performance.

## Why the Full Dataset is Not Included

GitHub does not allow files larger than 25MB to be uploaded directly through the web interface.
Since the dataset exceeds this limit, it is not included in the repository.

## How to Use the Dataset

Download the dataset from the Kaggle link above.

Place the dataset file (IMDB Dataset.csv) inside the project folder.

Run the project code or notebook to train and evaluate the models.

## Sample Dataset

A smaller dataset file (dataset_sample.csv) containing 5,000 reviews is included in this repository for quick testing and demonstration purposes.

## Technologies Used

* Python

* Pandas

* NumPy

* Scikit-learn

 * Matplotlib

* Natural Language Processing techniques


