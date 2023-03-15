# Iris Dataset Analysis and Linear Regression Model

## Description
This project analyzes the famous Iris dataset and builds a linear regression model to predict the sepal length of the Iris flowers.

The project uses various Python libraries such as Pandas, Seaborn, Matplotlib, and Scikit-learn to explore and visualize the dataset. It also utilizes the Linear Regression algorithm from Scikit-learn to build the prediction model.

## Installation
The project requires the following Python libraries:

Pandas
Seaborn
Matplotlib
Scikit-learn
Numpy
You can install the required libraries using pip:

```python
pip install pandas seaborn matplotlib scikit-learn numpy
```
## Dataset
The Iris dataset contains measurements of the sepal length, sepal width, petal length, and petal width for 150 Iris flowers. The dataset is commonly used for classification and clustering tasks in machine learning.

## Analysis
The project starts by importing the Iris dataset using Pandas and displaying the first few rows of the dataset. It then proceeds to visualize the dataset using various Seaborn plots such as scatter plots, box plots, violin plots, and pair plots.

Next, the project drops the "species" column from the dataset as it is not needed for the linear regression model. It then splits the dataset into training and testing sets using Scikit-learn's train_test_split function.

The project then builds a Linear Regression model using Scikit-learn's LinearRegression class and trains it on the training set. It makes predictions on the testing set and evaluates the model's performance using various metrics such as Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, and R-squared score.

## Conclusion
The project successfully analyzes the Iris dataset and builds a Linear Regression model to predict the sepal length of the Iris flowers. The model achieves 83.9% accuracy, indicating that it can be useful for predicting the sepal length of Iris flowers.
