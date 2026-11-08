# News Category Classification

A Natural Language Processing project that classifies news articles into four categories using traditional machine learning models.

## Dataset

[AG News Classification Dataset](https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset)

- 120,000 training samples
- 4 balanced categories:
  - World
  - Sports
  - Business
  - Sci/Tech

## Approach

1. Load and explore the dataset.
2. Clean and preprocess news titles and descriptions.
3. Combine titles and descriptions into a single text input.
4. Convert text into numerical features using TF-IDF.
5. Train and evaluate two classification models.

## Models

- Logistic Regression
- Multinomial Naive Bayes

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 89.10% |
| Multinomial Naive Bayes | 87.54% |

Logistic Regression achieved the best accuracy on the test set.

## Technologies

- Python
- Pandas
- NLTK
- Scikit-learn
- Matplotlib
- WordCloud

## Notebook

The `notebook.ipynb` file contains the complete workflow, including data exploration, preprocessing, model training, evaluation, and visualizations.

