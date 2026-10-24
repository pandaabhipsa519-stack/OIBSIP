# Iris Flower Classification

## 1. Project Overview

This project uses Machine Learning to classify Iris flowers
into three species: Setosa, Versicolor, and Virginica.

The classification is based on four flower measurements:
- Sepal length
- Sepal width
- Petal length
- Petal width

This project was developed as part of the Oasis Infobyte
Data Science Internship.

## 2. Objectives

- Explore and understand the Iris dataset.
- Perform Exploratory Data Analysis (EDA).
- Visualize feature distributions across flower species.
- Train and compare two Machine Learning classifiers.
- Evaluate model performance using standard metrics.

## 3. Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 4. Dataset

The Iris dataset is loaded directly from
`sklearn.datasets.load_iris()`.

It contains 150 samples, four numerical features,
and three flower species.

## 5. Project Workflow

1. Load the Iris dataset.
2. Inspect the dataset shape, data types, and missing values.
3. Calculate descriptive statistics.
4. Visualize data using pairplots and box plots.
5. Analyze feature importance using statistical F-scores.
6. Split data into training and testing sets using an 80/20 split.
7. Train Logistic Regression and Random Forest classifiers.
8. Evaluate both models and compare their results.
9. Select the better-performing model on the test set.

## 6. Model Evaluation Results

| Model | Test Accuracy |
|---|---:|
| Logistic Regression | 93.33% |
| Random Forest | 90.00% |

Logistic Regression achieved the higher accuracy on the
selected test set and was selected as the best-performing
model for this experiment.

## 7. Key Findings

- Both models classified all 10 Setosa test samples correctly.
- Most classification errors occurred between Versicolor
  and Virginica.
- The pairplot and box plots helped compare the four
  measurement features across species.
- Logistic Regression achieved 28 correct predictions
  out of 30 test samples.

## 8. How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn scikit-learn notebook`

3. Open Jupyter Notebook.
4. Open `Iris_Flower_Classification.ipynb`.
5. Run the notebook cells from top to bottom.

## 9. Limitations

The test set contains only 30 samples. The reported accuracy
may vary with a different train-test split or unseen data.
These results do not guarantee the same performance in
every real-world situation.

## 10. Conclusion

Two Machine Learning classifiers were trained and compared.
Logistic Regression achieved 93.33% test accuracy, compared
with 90.00% for Random Forest.

Further validation on additional data would be useful before
using the model in a real-world application.