# Car Evaluation Project

## Objective - Dimensionality Reduction
The UCI dataset contains car records that evaluates a model based on what is its overall acceptability from the perspective of consumers, along with other attributes that define a particular model. Using these attributes, correspondence analysis is performed in this project to identify key relationships between categories of each descriptive variable with how "acceptable" a car is. The complex "high-dimensional" relationships are boiled-down to lower dimensions for meaningful visualisation and easy interpretability.  Additionally, a linear classifier is constructed (using Discriminant Analysis) to predict a car's "acceptability" based on its attributes. 

## Programming Language
The entire project is performed using R using dedicated statistical packages such as **FactoMineR**.

## Dataset
Car Evaluation Dataset from UC Irvine Machine Learning Repository is used. The Car Evaluation Database contains examples with the structural information removed, i.e., directly relates car acceptability *(evaluation level)* to the six input attributes: buying, maint, doors, persons, lug_boot, safety.

Link for the dataset: *https://archive.ics.uci.edu/dataset/19/car+evaluation*<br>
All variables in the dataset are categorical. There are 1728 instances with no missing values for any of the variables.

## Categories of the variables used <br>
  **Categories of Car Evaluation *(Target variable in the original study)*:** <br>
  unacceptable, acceptable, good, very good <br><br>

  **Categories of input attributes *(Feature variables in the original study)*:**<br>
  buying price: vhigh, high, med, low<br>
  price of the maintenance: vhigh, high, med, low<br>
  number of doors: 2, 3, 4, 5more<br>
  capacity in terms of persons to carry: 2, 4, more<br>
  the size of luggage boot: small, med, big<br>
  estimated safety of the car: low, med, high
