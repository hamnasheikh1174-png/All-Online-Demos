# CodeNova Internship Projects

**Author:** Hamna Zahoor

## Project Overview

This README contains links and information about my CodeNova internship projects. The projects cover Exploratory Data Analysis, Machine Learning, and a Local Question-Answering Assistant.

## Task 1: Exploratory Data Analysis (EDA)

**Project Link:** [Open Task 1 in Google Colab](https://colab.research.google.com/drive/13hLOG3hrugvBtqOknPnvdoqa-b-qbL7D?usp=sharing)

### Objective
To explore and understand a dataset through data cleaning, statistical summaries, and visualizations.

### Main Activities
- Inspecting dataset structure and data types.
- Checking missing values and duplicate records.
- Identifying potential outliers.
- Exploring distributions and relationships between features.
- Creating visualizations such as histograms, boxplots, and correlation heatmaps.

### Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Task 2: House Price Prediction

**Project Link:** [Open Task 2 in Google Colab](https://colab.research.google.com/drive/1aMbvOMi4K9xyIFbJ2qMJc09I_NRlHgTS?usp=sharing)

### Objective
To build and evaluate a machine learning model for predicting house prices using the California Housing dataset.

### Main Activities
- Loading and exploring the dataset.
- Preparing features and the target variable.
- Splitting data into training and testing sets.
- Applying feature scaling where appropriate.
- Training a Linear Regression model.
- Evaluating predictions using MAE, RMSE, and R-squared.
- Visualizing model performance.

### Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

**Note:** Refer to the notebook for the actual evaluation results.

## Task 4: Local Question-Answering Assistant

**Project Repository:** [Open Task 4 on GitHub](https://colab.research.google.com/drive/1hYgZbibrWm2zU8F60VtZ6KpU1_T00lG2?usp=sharing)

### Project Overview
A local Python Question-Answering Assistant that retrieves relevant information from text documents using TF-IDF and cosine similarity. It displays source passages and handles unsupported questions without paid APIs.

### Technologies
- Python
- Scikit-learn
- TF-IDF
- Cosine Similarity

### Features
- Reads local text documents.
- Retrieves relevant passages.
- Displays source filenames and retrieval scores.
- Provides a fallback for unsupported questions.
- Works locally without requiring a paid API.

### Supported Test Questions
1. What does CodeNova provide?
2. What are CodeNova's internship tasks?
3. What skills can students develop during an internship at CodeNova?
4. What is Machine Learning?
5. What is supervised learning?
6. What is TF-IDF?
7. What is RAG?
8. What are common regression metrics?

### Unsupported Test Questions
1. What is the capital of France?
2. Who won the FIFA World Cup in 1998?

**Expected fallback:**
`Information not found in provided document`

### How to Run
1. Install dependencies using `pip install -r requirements.txt`.
2. Run `python app.py`.
3. Enter questions and review the answers and source passages.
4. Type `exit` to close the assistant.

## Live Demo Information

The links above provide access to notebooks and source code. They are not necessarily deployed, interactive live demos. A live demo URL should be added only when a project has been deployed to an accessible online platform.

## Conclusion

These projects demonstrate practical experience with data analysis, machine learning, model evaluation, and local document retrieval.

**Author:** Hamna Zahoor
