## PredictingWineQuality-PyCaret

# "Predicting Wine Quality: A Machine Learning Approach"

![image](https://user-images.githubusercontent.com/82657966/219924137-8648fc52-238d-4385-833d-d24e7ba10e51.png)

### References: [Red Wine Quality](https://www.kaggle.com/datasets/piyushgoyal443/red-wine-dataset) 

## Introduction

Are you a wine enthusiast with a passion for data analysis? If so, you're in for a treat with the Wine Quality dataset. Created in 2009, this publicly available dataset contains information on the physicochemical properties of red and white wines, as well as their sensory data as rated by experts. With 11 input variables and an output attribute of wine quality rated on a scale of 0 to 10, this dataset can be viewed as a classification or regression task. In fact, several data mining methods were applied to this dataset, with the support vector machine model achieving the best results. As a wine lover, you'll be fascinated by the correlations between fixed and volatile acidity, residual sugar, and alcohol percentage, to name a few. The Wine Quality dataset has 6,497 instances, and because the classes are ordered and not balanced, outlier detection algorithms can be used to detect the few excellent or poor wines. So, grab a bottle of Vinho Verde and let's explore the Wine Quality dataset!

## Goal

The goal is to use this dataset for research purposes, particularly in the fields of data mining, regression analysis, and feature selection.

|Input variables (based on physicochemical tests)|
|---|
|1 - fixed acidity (tartaric acid - g / dm^3)|
|2 - volatile acidity (acetic acid - g / dm^3)|
|3 - citric acid (g / dm^3)|
|4 - residual sugar (g / dm^3)|
|5 - chlorides (sodium chloride - g / dm^3|
|6 - free sulfur dioxide (mg / dm^3)|
|7 - total sulfur dioxide (mg / dm^3)|
|8 - density (g / cm^3)|
|9 - pH|
|10 - sulphates (potassium sulphate - g / dm3)|
|11 - alcohol (% by volume)|
|Output variable (based on sensory data):|
|12 - quality (score between 0 and 10)|

Missing Attribute Values: None

|Description of attributes|
|---|
1 - fixed acidity: most acids involved with wine or fixed or nonvolatile (do not evaporate readily)
2 - volatile acidity: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste
3 - citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines
4 - residual sugar: the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet
5 - chlorides: the amount of salt in the wine
6 - free sulfur dioxide: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine
7 - total sulfur dioxide: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine
8 - density: the density of water is close to that of water depending on the percent alcohol and sugar content
9 - pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale
10 - sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant
11 - alcohol: the percent alcohol content of the wine
Output variable (based on sensory data):
12 - quality (score between 0 and 10)


