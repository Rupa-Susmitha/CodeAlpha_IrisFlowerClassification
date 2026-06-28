# Iris Flower Classification

## Project Overview

This project is part of the **CodeAlpha Data Science Internship**.

The objective of this project is to build a Machine Learning classification model that predicts the species of an Iris flower based on four flower measurements.

The model classifies flowers into one of the following species:

* Setosa
* Versicolor
* Virginica

---

## Dataset

The Iris dataset is a built-in dataset available in Scikit-learn.

It contains:

* 150 flower samples
* 4 input features
* 3 flower species

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target

* Setosa
* Versicolor
* Virginica

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Project Workflow

1. Import required libraries.
2. Load the Iris dataset.
3. Create a Pandas DataFrame.
4. Perform Exploratory Data Analysis (EDA).
5. Visualize the dataset using charts.
6. Split the dataset into training and testing sets.
7. Train a Random Forest Classifier.
8. Predict flower species.
9. Evaluate the model using Accuracy, Classification Report, and Confusion Matrix.
10. Save the trained model.

---

## Model Used

* Random Forest Classifier

---

## Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## Project Structure

```text
CodeAlpha_IrisFlowerClassification/
│
├── Iris_Flower_Classification.ipynb
├── README.md
├── iris_model.pkl
├── requirements.txt
└── images/
```

---

## How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```text
Iris_Flower_Classification.ipynb
```

4. Run all the cells.

---

## Conclusion

The Random Forest Classifier successfully classified Iris flowers based on their measurements with excellent performance. This project demonstrates the complete machine learning workflow, including data preprocessing, visualization, model training, evaluation, and model saving.


## Project Visualizations

### 1. Species Count Plot

This graph shows the number of samples available for each Iris species. The dataset is balanced, with 50 samples for each class.

![Species Count Plot](images/Species%20Count%20Plot.png)


---

### 2. Pair Plot

The pair plot visualizes the relationship between all four features. It helps identify how well the different Iris species are separated based on their measurements.

![Pair Plot](images/Pair%20Plot.png)

---

### 3. Correlation Heatmap

The heatmap displays the correlation between numerical features. It helps understand which features have strong positive or negative relationships.

![Correlation Heatmap](images/Correlation%20Heatmap.png)


---

### 4. Confusion Matrix

The confusion matrix compares the actual species with the model's predicted species. Most predictions are on the diagonal, indicating excellent classification performance.

![Confusion Matrix](images/Confusion%20Matrix.png)
