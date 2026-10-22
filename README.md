# Titanic Survival Prediction

## Project Description
This project explores Titanic passenger data and builds machine learning classification models to predict whether a passenger survived. It is a beginner-friendly project demonstrating data exploration, preprocessing, model training, and evaluation.

## Objectives
- Explore passenger data and identify useful patterns.
- Clean and prepare features for machine learning.
- Train classification models to predict survival.
- Evaluate predictions using classification metrics.

## Tools and Technologies
- Python
- Jupyter Notebook
- NumPy and Pandas
- Matplotlib and Seaborn
- Scikit-learn

## Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Workflow
1. Load the `Titanic.csv` dataset.
2. Explore the data and visualize patterns.
3. Prepare features, including encoding categorical values.
4. Split the data into training and test sets.
5. Train classification models.
6. Evaluate predictions using accuracy, confusion matrix, and classification report.

## Repository Structure
```text
titanic-survival-prediction/
├── README.md
├── requirements.txt
├── titanic project.ipynb
└── Titanic.csv              # Include only if redistribution is permitted
```

## How to Run
1. Install Python 3.10 or newer.
2. Clone or download this repository.
3. Place `Titanic.csv` in the same folder as the notebook.
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Open the notebook in Jupyter:
   ```bash
   jupyter notebook
   ```
6. Run the notebook cells from top to bottom.

## Evaluation
The notebook uses accuracy, a confusion matrix, and a classification report to evaluate model predictions. Add the final metric values here after running the notebook successfully.

## Important Notes
- The dataset file must be named exactly `Titanic.csv` unless the notebook path is updated.
- For reliable evaluation, fit preprocessing tools such as `StandardScaler` on the training data only, then transform the test data. Avoid data leakage.
- Results depend on the dataset and preprocessing choices.

## Learning Outcomes
- Understand a basic classification workflow.
- Practice data exploration and categorical encoding.
- Compare multiple classification algorithms.
- Interpret common classification metrics.

## Disclaimer
This is an educational machine learning project, not a production prediction system.
