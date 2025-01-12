# Student Performance Analysis Using LMS Data

## Overview
This project analyzes a dataset of 480 student records collected from a learning management system (LMS) to predict and understand factors influencing academic performance. The dataset includes various demographic, behavioral, and academic features to classify students into three performance categories: low, medium, and high.

## Dataset
The dataset is publicly available on Kaggle: [xAPI-Edu-Data](https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data/data).

### Key Features:
- **Demographics**: Gender, nationality, educational stage, grade level, etc.
- **Behavioral**: Class participation, resource visits, and discussion involvement.
- **Parent Involvement**: Parent satisfaction levels and survey participation.
- **Performance Labels**: Classifies students into low, medium, and high-performance groups.

## Project Highlights
- **Exploratory Data Analysis (EDA)**:
  - Visualized key patterns in attendance, parent involvement, and resource usage.
  - Used heatmaps, bar plots, and box plots to uncover relationships between features and student performance.

- **Machine Learning Models**:
  - Implemented and evaluated classification models, including SVM, XGBoost, and Logistic Regression.
  - Used techniques such as feature engineering and handling imbalanced classes to optimize model performance.

- **Evaluation Metrics**:
  - Assessed models using accuracy, precision, recall, and F1-score to identify the best-performing algorithm.

## Results
- Students with high engagement in class activities (e.g., discussions, raising hands) and frequent resource visits tend to perform better.
- Parent satisfaction and fewer absences correlate strongly with high performance.
- The best-performing model achieved an accuracy of **80%**.

## Project Structure
```
Student_Performance_Analysis/
│
├── data/
│   └── xAPI-Edu-Data.csv         # Dataset
│
├── notebooks/
│   ├── Enhancing_Student_Success.ipynb                
│
├── README.md                     # Project overview and instructions
```


## Future Work
- **Deployment**: Build a web app for educators to input data and receive performance predictions.
- **Feature Expansion**: Incorporate additional data sources (e.g., standardized test scores).

