
# Statistical Analysis and Personalized Book Recommendation System Based on User Preference Data

**M.Sc. Data Science – Major Capstone Project 2**

## 1. Project Overview

The **Statistical Analysis and Personalized Book Recommendation System** is a data science project that combines statistical analysis, machine learning, and recommendation techniques to provide personalised book suggestions based on user preferences.

The project analyses book ratings and user-preference data to identify patterns, understand reading behaviour, and recommend relevant books.

It implements a hybrid recommendation approach by combining Content-Based Filtering and Collaborative Filtering to improve recommendation relevance and provide personalised suggestions.

## 2. Problem Statement

With a large number of books available across different categories, readers may find it difficult to discover books that match their interests and preferences.

Traditional browsing methods do not always provide personalised recommendations.

This project addresses the problem by analysing user-preference data and developing a recommendation system that suggests books based on book characteristics and user-rating patterns.

## 3. Project Objectives

- Development of a Hybrid Book Recommendation System.
- Handling Cold Start and Data Sparsity Problems.
- Enhancing Personalization Using User Preference Data.
- Improving Scalability and Computational Efficiency.
- Evaluating Recommendation Quality and System Performance.

## 4. Key Features

- **Data Analysis:** Explore book ratings, user preferences, and data distributions.
- **Statistical Analysis:** Apply descriptive statistics, correlation analysis, and hypothesis testing.
- **Content-Based Filtering:** Recommend books based on textual similarity using TF-IDF and Cosine Similarity.
- **Collaborative Filtering:** Generate recommendations using user–book rating patterns with SVD.
- **Hybrid Recommendation:** Combine content-based and collaborative approaches.
- **Personalised Suggestions:** Generate recommendations based on user preferences.
- **Interactive Application:** Use Streamlit to provide an interactive user interface.
- **Model Evaluation:** Assess recommendation performance using RMSE and MAE.

## 5. Technologies and Tools Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Statistical Analysis | SciPy |
| Machine Learning | Scikit-learn, Scikit-Surprise |
| Recommendation Techniques | TF-IDF, Cosine Similarity, SVD |
| Data Visualization | Matplotlib, Seaborn |
| Application Development | Streamlit |
| Development Environment | Jupyter Notebook |

## 6. Methodology

The project follows these major stages:

### 6.1 Data Collection and Understanding
- Load the book and user-preference datasets.
- Understand the dataset structure, attributes, and data types.
- Examine book information and user-rating records.

### 6.2 Data Preprocessing
- Handle missing and inconsistent values.
- Prepare relevant features for analysis.
- Transform data into suitable formats for recommendation modelling.

### 6.3 Exploratory Data Analysis (EDA)
- Analyse book-rating distributions.
- Explore user preferences and rating patterns.
- Identify trends and relationships in the dataset.
- Use visualisations to understand the data.

### 6.4 Statistical Analysis
Apply statistical techniques to understand the underlying data:

- Descriptive Statistics
- Pearson Correlation
- Independent Sample t-test
- Analysis of Variance (ANOVA)

### 6.5 Content-Based Filtering

Content-Based Filtering recommends books based on their similarities.

- Convert book text into numerical representations using TF-IDF.
- Calculate similarity between books using Cosine Similarity.
- Recommend books with similar content.

### 6.6 Collaborative Filtering

Collaborative Filtering identifies patterns in user–book interactions.

- Analyse user-rating patterns.
- Apply Singular Value Decomposition (SVD).
- Predict user preferences based on learned rating patterns.
- Generate personalised recommendations.

### 6.7 Hybrid Recommendation System

The hybrid approach combines Content-Based Filtering and Collaborative Filtering.

- Content-Based Filtering identifies books with similar characteristics.
- Collaborative Filtering identifies books based on user-rating patterns.
- Both approaches contribute to generating personalised recommendations.

### 6.8 Model Evaluation

Evaluate recommendation performance using:

- **RMSE (Root Mean Squared Error):** Measures the difference between actual and predicted ratings.
- **MAE (Mean Absolute Error):** Measures the average absolute prediction error.

## 7. System Workflow

The overall workflow of the project is:

**Dataset → Data Preprocessing → Exploratory Data Analysis → Statistical Analysis → Recommendation Models → Hybrid Recommendation System → Personalised Book Suggestions**

## 8. Repository Directory Structure

```text
statistical-analysis-personalized-book-recommendation/
│
├── README.md
├── bookrecomdationsystem1.ipynb
├── Project_Thesis.pdf
├── PROJECT SYNOPSIS-1.pdf
├── Project-Persentation1.pdf
└── Project-Presentation 2.pdf

## 9. Installation and Execution

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python libraries

### Step 1: Clone the Repository

```bash
git clone https://github.com/Alekhya-commits/statistical-analysis-personalized-book-recommendation.git
```

### Step 2: Navigate to the Project Directory

```bash
cd statistical-analysis-personalized-book-recommendation
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Open the Jupyter Notebook

```bash
jupyter notebook
```

Open `Book_Recommendation_System.ipynb` and execute the notebook cells in sequence.

### Step 5: Run the Streamlit Application

If the application is available as a separate Python file named `app.py`, run:

```bash
streamlit run app.py
```

*Ensure the notebook filename, dataset paths, and application filename match the actual repository.*

## 10. Model Evaluation

The recommendation system uses the following evaluation metrics:

| Metric | Description |
|---|---|
| RMSE | Measures the square root of the average squared prediction errors. |
| MAE | Measures the average absolute difference between actual and predicted ratings. |

**Final Model Results:**

- **RMSE:** 3.5040
- **MAE:** 2.8168

These metrics evaluate the difference between the actual user ratings and the ratings predicted by the recommendation model.

## 11. Project Documentation

The complete academic documentation, including the project methodology, statistical analysis, model development, conclusions, bibliography, and supporting material, is provided separately.

**Project Thesis:** `Project_Thesis.pdf`


# 12. Future Scope

- Improve recommendation accuracy using advanced hybrid recommendation techniques.
- Incorporate additional user preferences and book metadata.
- Improve recommendations for new users and newly added books.
- Explore deep learning-based recommendation approaches.
- Enhance the application with user profiles, reading history, and feedback-based recommendations.
- Deploy the recommendation system as a scalable web application.

# 13. Conclusion

This project demonstrates the application of statistical analysis and machine learning techniques in developing a personalised book recommendation system.

By combining Content-Based Filtering and Collaborative Filtering, the system aims to provide relevant book suggestions based on book characteristics and user-preference patterns.

The project provides practical experience in data preprocessing, exploratory data analysis, statistical testing, recommendation modelling, model evaluation, and application development.

## 14. Author

Alekhya Varkolu

M.Sc. Data Science  
University Post Graduate College, Osmania University  
Hyderabad, Telangana, India
