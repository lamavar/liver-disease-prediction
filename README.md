# Machine Learning Engineer Nanodegree
## Liver disease prediction

Predicting liver disease in patients using Machine Learning.

### Problem Statement
Given a dataset containing biological and diagnostic data of 583 Indian patients, this
project aims to identify a suitable machine learning algorithm which is capable of
identifying whether a person has liver disease or not.

This is a binary classification problem to be solved using supervised learning. We have ten
features for each data point and a label which identifies whether the patient is suffering
from liver disease or not. In order to arrive at the solution, our aim should be to train
various supervised learning models on this dataset so that we have a well performing
model which is able to classify any new data point as a positive or negative with a
reasonable degree of accuracy and perform better than the benchmarks.

### Data
The data set contains 416 liver patient records and 167 non liver patient records collected
from North East of Andhra Pradesh, India. The "Dataset" column is a class label used to
divide groups into liver patient (liver disease) or not (no disease). This data set contains
441 male patient records and 142 female patient records.
Any patient whose age exceeded 89 is listed as being of age "90".

**Features**
- Age of the patient
- Gender of the patient
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphotase
- Alamine Aminotransferase
- Aspartate Aminotransferase
- Total Protiens
- Albumin
- Albumin and Globulin Ratio
- Dataset: field used to split the data into two sets (patient with liver disease, or no
disease)

### Software Used

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/index.html)

This project requires also requires `visuals.py` file