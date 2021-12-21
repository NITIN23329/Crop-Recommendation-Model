# Crop Recommendation Model

## Introduction : 
This machine learning project aims to find the best suitable crop for agricultural land by learning from the past yielded crops. Various factors are considered for determining the best yielding crop, such as the climate, which includes rainfall, temperature, and the soil contents such as the pH level, nutrient content such as N, P, K of the soil, and more. Several machine learning algorithms have been applied during this project, making performance comparisons.



## Libraries used in project
1) Pandas
2) Numpy
3) Seaborn
4) Matplotlib
5) Scikit-learn

## Features in dataset : The dataset consist of 70k samples
The features for our model are:

1) Rainfall in mm
2) Temperature in Celsius
3) Humidity
4) pH level of soil
5) Nitrogen (N) level of soil.
6) Phosphorous (P) level of soil.
7) Potassium (K) level of soil
8) Iron (Fe) level in soil
9) Calcium (Ca) level of soil
10) Magnesium (Mg) level of soil
11) Sulphur (S) level of soil
12) Manganese (Mn) level of soil

## Output of model : 
Multiclass classification output : Crop name
22 different types of crop can be predicted.

## Data - Preprocessing :
1) Removed unnecessary features
2) Removed skewed features(if any)
3) Histogram plotting of feature
4) Normalization

## Exploratory Data Analysis
1) Corellation heat map
2) Pair-grid plot
3) Relational plot
4) Data distribution plot

## ML Algorithm utilized : 
1) Logistic Regression
2) Naive Bayes
3) Decision Tree
4) Decision Tree with Ada Boosting
5) Random Forest
6) Support Vector Machine
7) Aritifical Neural Network


## Inferences from this ML Model : 
1) Naive-bayes has least accuracy, around 40 % . This is because naive bayes assume independency of features which is not a case in practical scenario.
2) Logistic Regression performs okay-ish (77%). Can be taken as a baseline classifier
3) Decision Tree has less accuracy(72%) as it is generally the case that Decision Tree overfit our training data.
4) Random Forest (92%) eleminate the overfitting drawback of DT by taking Majority Voting.
5) Decision Tree with adaboost(90%) "learn from your Mistakes". 
6) Neural Network(98%) and SVM(96%) perform very well  and it is quite reasonable due to their complexity and they are strong classifiers.
7) The best model is Neural Network having accuray of 98%. On the other hand it has high complexity .

## Accuracy Comparision of different ML Model

![Accuracy](https://user-images.githubusercontent.com/55681638/146889909-537c3c6a-fa37-4cb0-bd9d-da196e7d95f2.png)



 
