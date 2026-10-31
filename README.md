# Week 4: Machine Learning Model Development and Evaluation

## Project Overview
This project focuses on developing and evaluating machine learning models using Python and Scikit-learn. The Titanic passenger dataset is used to predict whether a passenger survived the disaster.

The project demonstrates the complete machine learning workflow, including data preprocessing, model selection, training, evaluation, and visualization.

## Objectives
- Prepare and clean the Titanic dataset.
- Handle missing values and encode categorical variables.
- Build machine learning classification models.
- Evaluate model performance using different metrics.
- Compare models through visualizations.
- Identify potential errors and suggest improvements.

## Dataset
- **Dataset:** Titanic Passenger Dataset
- **Source:** [Titanic Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- **Records:** 891 passengers
- **Target Variable:** Survived (0 = No, 1 = Yes)

## Machine Learning Algorithms
1. Logistic Regression
2. Decision Tree Classifier

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Data Preprocessing
- Handling missing numerical values using median imputation.
- Handling missing categorical values using most frequent imputation.
- Encoding categorical variables using One-Hot Encoding.
- Scaling numerical features.
- Splitting data into training and testing sets.

## Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Visualizations
- Model performance comparison chart.
- Confusion matrices.
- ROC curve comparison.

## Project Structure
```text
Week_4_Titanic_ML_Project/
│
├── Week4_Titanic_ML_Model_Development.ipynb
├── README.md
└── figures/
```

## How to Run
1. Download or clone this repository.
2. Open the Jupyter Notebook in Google Colab.
3. Run all cells using Runtime → Run all.
4. The dataset will be loaded automatically.
5. Review the evaluation metrics and generated visualizations.

## Conclusion
This project demonstrates how machine learning algorithms can be used to solve a classification problem. Logistic Regression and Decision Tree models are trained and evaluated to understand their performance, strengths, and limitations.

The project also highlights the importance of data preprocessing, model evaluation, and avoiding overfitting when developing reliable machine learning solutions.

## Author
Created as part of the Week 4 Data Science with Python project.
