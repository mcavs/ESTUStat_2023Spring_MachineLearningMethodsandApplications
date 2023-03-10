# Homework #1: Regression task

## Tasks

Task 1: Prediction of median house prices for California districts (https://www.kaggle.com/datasets/camnugent/california-housing-prices)

Task 2: Prediction of insurance costs (https://www.kaggle.com/datasets/mirichoi0218/insurance)

Task 3: Prediction of football player values (https://www.kaggle.com/datasets/bryanb/fifa-player-stats-database?select=FIFA23_official_data.csv)

Task 4: Prediction of red wine qualities (https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

Task 5: Prediction of second-hand car prices (https://www.kaggle.com/datasets/mayankpatel14/second-hand-used-cars-data-set-linear-regression)


## Assignments

You can find your assignment with your initial (Example: the inial for Ali Yılmaz is AY). The tasks are assigned you randomly. 

Task 1: EK, RK, HK, ŞG, ŞT, GG

Task 2: DRB, Sİ, HD, MEA, MD, ÖNT

Task 3: BT, EA, AA, MY, EB, BÇ

Task 4: GA, SÖ, FK, BEA, YÖ, BYÖ

Task 5: ET, BÇ, BT, MAT, FG, ZÖ


## Instructions

1. Detail your task with the problem, features, and target. 
2. Describe the dataset in your task in terms of the dimension, variable type, and some other that you want to add.
3. Train a linear regression model.
4. Report the performance of the trained model with only one metric that you learned in the lecture and share the reason why you chose the metric.
5. Check any problem related to over and underfitting.
6. Create a new observation (it is up to you, just create an observation with the feature values you want), and predict the value of its target feature.


## Grading

* Please prepare a report in PDF format by using Quarto or Jupyter Notebook (**no any other pubishing tool!**) consisting the points in the instructions in your task.
* The report must be submitted until Mar 25, 23:59 to this repository with your initial. **Late submissions are not be evaluated.**
* All items in the instructions must be done with interpretated (Explain what you did and find). 
* **The assignment will not be evaluated if any of the above items are not met.**


## Tips

* If there is a categorical feature in the inputs, you must specify it in the R function as follows: 

    `lm(target ~ featureA + featureB + factor(featureC), data = train)`

* If the data consist 'NA', you can exlude or imput them as follows:
    
    `data <- na.exclude(data)`
    
* You have any problem with R, you may find the solution of your problem in https://www.youtube.com/watch?v=Q96d0heoMrw
