# kaggle-otto-classification
My solution to [Otto Group Product Classification Challenge](https://www.kaggle.com/c/otto-group-product-classification-challenge) (Top 4%, 107th of 3514).

## Overview
In this competition, I'm challenged to classify more than 200,000 products from Otto Group into 9 main product categories.

My solution is a 2-fold stacking classifier that ensembles multiple machine learning algorithms, including **k-Nearest Neighbors (KNN)**, **Logistic Regression (LR)**, **Random Forest (RF)**, **Gradient Boosting Classifier (XGB)**, and **Neural
Networks (NN)**.The model achieved 82.4% accuracy rate in the test dataset.

Below is my solution diagram.
<br><br>
<img src="images/solution_diagram.png" width="750">

## Running
`python ensemble_train.py`

Prediction will be saved as `submission_DATETIME.csv`.
## Requirements
### Dataset
[Otto group product classification dataset](https://www.kaggle.com/c/otto-group-product-classification-challenge/data) - put `train.csv` and `test.csv` in the top level of this repository.
### Dependencies
Install Python dependencies using `pip install -r requirements.txt`.