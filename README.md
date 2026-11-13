# Book Recommendation System

## Project Overview

The Book Recommendation System is a Machine Learning project that recommends books to users based on similarities in book rating patterns.

This project uses **Item-Based Collaborative Filtering** and **Cosine Similarity** to identify similar books and generate personalised recommendations.

## Project Objectives

- Analyse book ratings and user preferences.
- Explore popular books and rating patterns.
- Build a book recommendation system using collaborative filtering.
- Calculate similarities between books using Cosine Similarity.
- Evaluate model performance using Precision@10 and Recall@10.

## Dataset

The project uses the **Book-Crossing Dataset**, downloaded from Kaggle.

The dataset contains information about books, users and ratings.

The dataset files are not included in this repository. Download the dataset from Kaggle and place the required CSV files in the appropriate data folder.
Link to Kaggle Dataset --> saved to Downloads folder
https://www.kaggle.com/datasets/ruchi798/bookcrossing-dataset

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology

1. Data Loading and Understanding
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Popularity-Based Recommendation
5. User and Book Filtering
6. User-Book Matrix Creation
7. Cosine Similarity Calculation
8. Building the Recommendation Function
9. Model Evaluation
10. Model Comparison

## Model Evaluation

Two Item-Based Collaborative Filtering approaches were evaluated using Precision@10 and Recall@10.

| Model | Precision@10 | Recall@10 |
|---|---:|---:|
| Original Item-Based CF | 0.0257 | 0.0915 |
| Weighted Item-Based CF | 0.0006 | 0.0025 |

The original Item-Based Collaborative Filtering model performed better than the weighted approach on the evaluation dataset.

## Sample Recommendation

For the input book **The Joy Luck Club**, some recommendations include:

- The Hundred Secret Senses
- The Kitchen God's Wife
- The Sparrow
- All the Pretty Horses

## Limitations

- Cold Start Problem
- Data Sparsity
- Popularity Bias
- Limited recommendation accuracy

## Future Scope

- Implement hybrid recommendation systems.
- Explore advanced recommendation algorithms.
- Incorporate additional user preferences.
- Develop a web application for book recommendations.

## Author

**Pooja Kallupothula**

MSc Data Science Student

This project was developed as part of my MSc Data Science academic work.
